# Contributions

Dziękujemy za zainteresowanie i chęć wniesienia wkładu do tego projektu! Doceniamy Twój czas i wysiłek. Oto kilka wskazówek, które pomogą Ci zacząć.

---

## Jak wnieść wkład

1. **Zforkuj repozytorium**: Stwórz kopię tego repozytorium na swoim koncie GitLab, klikając przycisk „Fork” na górze.
2. **Sklonuj swojego forka**: Sklonuj zforkowane repozytorium na swój lokalny komputer za pomocą komendy:

   ```bash
   git clone https://gitlab.com/twoja-nazwa-użytkownika/nazwa-projektu.git 
   ```

3. **Utwórz gałąź**: Stwórz nową gałąź dla swoich zmian:

   ```bash
   git checkout -b twoja-nazwa-gałęzi
   ```

4. **Wprowadź zmiany**: Zaimplementuj swoje zmiany w tej gałęzi.
5. **Przetestuj swoje zmiany**: Upewnij się, że Twoje zmiany działają poprawnie, uruchamiając odpowiednie testy lub skrypty projektu.
6. **Zacommituj swoje zmiany**: Napisz jasny komunikat commit, opisujący wprowadzone zmiany:

   ```bash
   git add .
   git commit -m "Opis zmian"
   ```

7. **Wyślij na GitLab**: Wyślij swoje zmiany do swojego forka:

   ```bash
   git push origin twoja-nazwa-gałęzi
   ```

8. **Utwórz Pull Request**: Otwórz pull request (PR) z Twojego forka do głównego repozytorium, wyjaśniając, co zrobiłeś i dlaczego jest to przydatne.

## Kodeks postępowania

Prosimy o szacunek i uwzględnienie innych podczas wniesienia wkładu. Wszyscy współtwórcy są zobowiązani do przestrzegania [Kodeksu Postępowania](CODE_OF_CONDUCT.md).

## Zgłaszanie problemów

Jeśli napotkasz błędy, masz sugestie lub coś jest niezrozumiałe, otwórz zgłoszenie w sekcji [Issues](https://gitlab.com/nazwa-projektu/issues) repozytorium. Podczas zgłaszania problemu prosimy o podanie:

- Jasnego opisu problemu.
- Kroków do odtworzenia problemu.
- Odpowiednich plików logów, komunikatów o błędach lub zrzutów ekranu.

## Wytyczne dotyczące commitów

- Używaj jasnych i zwięzłych komunikatów commit.
- Przestrzegaj specyfikacji [Conventional Commits](https://www.conventionalcommits.org/) dla opisów commitów:
  - `feat`: Nowa funkcja
  - `fix`: Poprawka błędu
  - `docs`: Zmiany w dokumentacji
  - `style`: Zmiany w stylu kodu (np. formatowanie)
  - `test`: Dodawanie lub aktualizacja testów
  - `refactor`: Refaktoryzacja kodu bez zmiany zachowania
