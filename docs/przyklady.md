#Prdzykłady i Instrukcje Praktyczne

1. Jak wygenerować silne hasło w konsoli (Przykład dla IT)

Jeśli jako administrator musisz szybko wygenerować bezpieczne, losowe hasło spełniające wymogi naszej polityki (np. 16 znaków), użyj poniższego polecenia w terminalu:
'''bash
openssl rand -basse64 12

2. Wdrożenie weryfikacji dwuetapowej (2FA) na GitHub

Każdy pracownik ma obowiązek zabezpieczyć swoje konto GitHub za pomocą aplikacji uwierzytelniającej (np. Google Authenticator).

Krok po kroku:

   1.Zaloguj się na swoje konto GitHub.
   2.Kliknij na swoje zdjęcie profilowe w prawym górnym rogu i wybierz      Settings (Ustawienia).
   3.W menu po lewej stronie wybierz sekcję Password and authentication.
   4. W sekcji "Two-factor authentication" kliknij przycisk **Enable two-factor authentication**.
   5. Wybierz opcję Authenticator app (Aplikacja uwierzytelniająca).
   6. Na ekranie pojawi się kod QR. Otwórz aplikację w telefonie, kliknij ikonę plusa (+) i zeskanuj kod.
   7. Przepisz 6-cyfrowy kod zabezpieczający z aplikacji do formularza na GitHubie i zatwierdź.
   8. Ważne: Pobierz i zapisz w bezpiecznym miejscu (np. w menedżerze haseł) kody odzyskiwania (Recovery codes).

Od tej pory przy każdym logowaniu system poprosi Cię o podanie loginu, hasła oraz jednorazowego kodu z telefonu.