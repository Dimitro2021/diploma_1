# Аналіз експертиз та дозвільних документів у будівництві

Цей репозиторій містить код та підготовлені дані для аналізу експертиз проектно-кошторисної документації (ПКД) та дозвільних документів у сфері будівництва.

## Структура проєкту

- `expertise/` — оброблені дані експертиз та пов'язані ноутбуки для аналізу.
- `permit_documents/` — оброблені дані дозвільних документів.
- `permit_documents/parsed_chunks/` та `permit_documents/tep_chunks/` — зпосіб зберігання даних (надто великі дані, тому на гугл диску).
- `requirements.txt` — список необхідних бібліотек Python.

## Дані

Більшість підготовлених датасетів зберігаються у форматі `.csv` та використовуються у відповідних Jupyter-ноутбуках для аналізу або ж результати агнегації даних.

**Великі файли** (>100MB), які не були завантажені у репозиторій, доступні за посиланням на Google Drive:

👉 [Посилання на файли expertise_english_columns.csv](https://drive.google.com/drive/folders/1N7vooR2KjuwRBv_dvochaCQpayFNBqAu?usp=sharing)

Також там збегігається усі `.ipynb` файли у форматі Google Colab, графіки, згенеровані бібліотекою plotly, github не розпізнає.

Аналіз Експертиз:
  - Основна робота - аналіз експертиз, виконана у файлі `expertise\expertise_analysis.ipynb` [Google Colab](https://drive.google.com/file/d/1F7kbPxlGI_Dna_3uT2vtWXlWW8-ZetXP/view?usp=sharing)
  - Парсинг реєстру експертиних організацій `expertise\expertise_organisation_page_parer.ipynb` [Google Colab](https://drive.google.com/file/d/1LG71JtxwXCyVaDmuLHbTDcX2Q7Lpdsa2/view?usp=sharing)
  - Парсинг реєстру експертиз `expertise\expertise_page_parcer.ipynb` [Google Colab](https://drive.google.com/file/d/1Vgze5r76nlrUHZvMBeiJfY7DisYmx0D5/view?usp=sharing)


Аналіз lозвільних документів:
  - Парсинг реєстру дозвільних документів та техніко-економічного моделювання `permite_documents\permit_page_parcer.ipynb` [Google Colab](https://drive.google.com/file/d/1OldUlIsBcYIe_FpBrXiASNFshyaCj_Bu/view?usp=sharing)
  - Частковий аналіз дозвільних документів `permite_documents\permit_page_analysis.ipynb` [Google Colab](https://drive.google.com/file/d/1qSCN-pqDzwWmdAZSvYyClhZ7Kk8jHikf/view?usp=sharing)


