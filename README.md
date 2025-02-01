# 🛠️ Skrypty do automatyzacji e-commerce i codziennych zadań

To repozytorium zawiera skrypty do automatyzacji różnych procesów związanych z e-commerce oraz codziennymi zadaniami. Celem projektu jest oszczędność czasu i eliminacja powtarzalnych działań poprzez wykorzystanie Python oraz API popularnych platform.

## 🚀 Funkcjonalności
PhotoDownloader
- Pobieranie zdjęć z listy linków w pliku txt 
  - Skalowanie do kwadratu na podstawie dłuższej krawędzi np. z 300x500, spowoduje dodanie tła i przeskalowanie do 500x500
  - Konwertowanie róźnych formatów na jpg (w przypadku .png dodaje białe tło pod grafikę)
  - Wykrywanie sytuacji, w której zdjęcie produktowe "dotyka krawędzi" i dodanie obwódki w celu poprawy jakości za pomocą openCV
  - Możliwość dodania znaku wodnego na podstawie 


## 🔧 Instalacja

### Pobranie konkretnego folderu
Jeśli chcesz pobrać tylko wybrany folder, użyj:
```sh
git clone --no-checkout https://github.com/xeqas/automation-scripts.git
cd automation-scripts
git sparse-checkout init --cone
git sparse-checkout set nazwa_folderu_do_pobrania
git checkout
```
📌 Uwaga: Upewnij się, że nazwa_folderu_do_pobrania jest poprawna i istnieje w repozytorium.


*Projekt dostępny na licencji MIT. Możesz go dowolnie modyfikować i używać do własnych celów.*
