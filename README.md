# IdeFunctionLab

## Cel
Program oblicza funkcję f(x) = 2x + 3.

## Uruchomienie
Polecenie: `dotnet run`
Przykład: dla x = 4 wynik to f(4) = 11.

## Sprawdzenie w IDE

### VS Code
- Kompilacja: `dotnet build` zakończona powodzeniem.
- Uruchomienie: `dotnet run` wypisało `f(4) = 11`.
- Debugger: przy pierwszym breakpointcie (`return 2 * value + 3;`) `value = 4`, przy drugim (`Console.WriteLine`) `result = 11`. Program wznowiony bez błędów.

### Visual Studio
- Kompilacja: Build Solution zakończone powodzeniem.
- Uruchomienie: Start Without Debugging wypisało `f(4) = 11`.
- Debugger: w oknie Locals `value = 4` przy pierwszym breakpointcie, `result = 11` przy drugim. Program wznowiony bez błędów.

### Rider
- Kompilacja: Build Solution zakończone powodzeniem.
- Uruchomienie: Run wypisało `f(4) = 11`.
- Debugger: w oknie debuggera `value = 4` przy pierwszym breakpointcie, `result = 11` przy drugim. Program wznowiony bez błędów.

## Dodatkowe sprawdzenie
Dla x = -2 wynik wyniósł `f(-2) = -1`. Po sprawdzeniu przywrócono x = 4.