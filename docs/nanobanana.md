# Nano Banana (Image generation)

**Nano Banana** to nazwa natywnych możliwości generowania obrazów w Gemini API. [page:1] Obecnie obejmuje dwa różne modele dostępne w Gemini API. [page:1]

- **Nano Banana** – model **Gemini 2.5 Flash Image** (`gemini-2.5-flash-image`), zaprojektowany pod kątem szybkości i wydajności, zoptymalizowany do zadań o dużej przepustowości i niskim opóźnieniu. [page:1]  
- **Nano Banana Pro** – model **Gemini 3 Pro Image Preview** (`gemini-3-pro-image-preview`), przeznaczony do profesjonalnej produkcji assetów, wykorzystujący zaawansowane rozumowanie („Thinking”) do realizacji złożonych instrukcji i renderowania wysokiej jakości tekstu. [page:1]

---

## Get started

Obrazy można generować przy użyciu metody `generate_content` z nazwą modelu odpowiadającą wybranej wersji. [page:1]

### Przykład (Python)

```
from google import genai
from PIL import Image

client = genai.Client()

response = client.models.generate_content(
    model="gemini-2.5-flash-image",
    contents="Create a picture of a futuristic banana with neon lights in a cyberpunk city.",
)

for part in response.parts:
    if part.inline_data:
        image = part.as_image()
        image.show()
```

[page:1]

---

## Learn more

Dla pełniejszej dokumentacji dotyczącej generowania obrazów, edycji, zaawansowanego promptowania oraz porównań modeli dostępne są następujące przewodniki. [page:1]

- **Image generation with Gemini** – kompletny przewodnik po używaniu modeli Nano Banana i Nano Banana Pro:  
  https://ai.google.dev/gemini-api/docs/image-generation [page:1]  
- **Model information** – szczegóły wersji modeli, możliwości oraz ceny:  
  https://ai.google.dev/gemini-api/docs/models/gemini [page:1]

