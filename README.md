# NAI
Czwiczenia z NAI PJATK-Gdańsk 2020

Tutaj bedą się znajdować czwiczenia które zostały wykonywane na Laboratoriach z przedmiotu NAI

                                                Lab1 13.10.2020
Niech program który jest w Twoim repozytorium będzie wyświetlał odbicie lustrzane tego co widzi kamerka.
Niech też program się zakończy w momencie wciśnięcia klawisza ESC

                                                Lab2 20.10.2020
Pobierze z kamery klatkę obrazu
Rozmyje obraz za pomocą rozmycia Gaussa (parametry wybierz sobie takie, jak Tobie wydadzą się odpowiednie)
Przeskaluje ją do rozmiaru takiego, jak podany w argumencie wywołania Twojego programu (czyli będzie można z linii komend powiedzieć jak wielki ma być obrazek). Jeśli nie podano argumentów, niech będzie to 320x200
Przekształci przestrzeń barw do formatu HSV (niech to pojawia się w okienku)
Dokona operacji inRange dla zadanych zakresów - zakresy niech będą podane za pomocą suwaków. (to będzie drugie okienko)
Wartości zakresów niech pojawiają się w okienku z obrazem w wersji HSV
Jeżeli użytkownik naciśnie klawisz <x> to zostanie zrobione "zdjęcie" wybranego przez użytkownika fragmentu obrazu - wybieramy ROI. To zdjęcie niech zostanie zapisane na dysk pod nazwą taką, jak sobie wymyślisz. Podpowiem, że można skorzystać z imwrite

                                                Lab3 27.10.2020
  Napisz program, który będzie wyłapywał 2 największe obiekty wybranego koloru (wybierz kolor, polecam kolory bardzo jaskrawe) i jak zostaną ułożone w jednej linii (z jakimś marginesem) to między nimi zostanie narysowane coś. Niech to coś będzie w stylu (do wyboru) odcinek, obrazek pioruna, obrazek miecza świetlnego, czy czegokolwiek innego.
  
                                                Lab4 03.11.2020
Wyobraźmy sobie, że mamy do zeskanowania dokument. Chcielibyśmy, aby zawsze był on poprawnie zorientowany (góra u góry, dół na dole, a nie do góry nogami). Nie mamy skanera, więc musimy skorzystać z aparatu w telefonie lub w laptopie.
Zasada działania: Użytkownik kładzie kartkę do "zeskanowania" na ciemnym stole, a następnie kładzie na kartce marker (na przykład coś o kolorze różowym) w prawym dolnym rogu tej kartki. Kieruje kamerę na tą kartkę. Program wyłapuje prostokątną kartkę papieru, sprawdza czy jest na niej marker, jeśli tak, to robi zdjęcie, poprawia perspektywę tak aby kartka była prostokątna, obraca jeśli trzeba tak aby marker był na dole i zapisuje na dysku. Może zapisywać na przykład serię tak zeskanowanych kartek w celu umożliwienia użytkownikowi wyboru najlepszego skanu.                                                
                                                
                                                Lab5 10.11.2020
