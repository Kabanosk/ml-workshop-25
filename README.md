# Zajęcia z Machine Learning dla uczniów szkół średnich z Wrocławia

W tym repozytorium znajdziesz wykłady i listy ćwiczeniowe pokazane na zajęciach z Machine Learning dla uczniów Wrocławskich szkół średnich.

## Struktura plików
```markdown
ml-workshop-25
├── exercises  # Zadania praktyczne
└── lectures   # Notebooki z wykładów
```

## Jak uruchomić notebooki
### Wersja prosta
Aby uruchomić notebooki, możesz je zaimportować do Google Colab. Wystarczy otworzyć [Google Colab](https://colab.research.google.com/), a następnie wgrać odpowiedni plik z katalogu notebooks.

### Wersja trudna (ale może nie aż tak trudna)
Zainstalować [Jupyterlab](https://jupyter.org/install). Zaletą tego jest to, że możemy to uruchomić na własnym komputerze co w pewnych przypadkach może być szybsze niż uruchamianie na Google Colab.

### Wersja z użyciem poetry 
1. Zainstalować `poetry` na przykład z użyciem `pip install poetry`.
2. Zainstalować odpowiednie paczki za pomocą `poetry install`.
3. Odpalamy notebook za pomocą `poetry run jupyter notebook`

