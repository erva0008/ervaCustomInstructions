# When answering questions about frameworks, libraries, or APIs, use Context7 to retrieve current documentation   rather than relying on training data.

# C# Development

## C# Instructions
- Always use the latest version C#, currently C# 13 features.
- Write clear and concise comments for each function.

## General Instructions
- Make only high confidence suggestions when reviewing code changes.
- Write code with good maintainability practices, including comments on why certain design decisions were made.
- Handle edge cases and write clear exception handling.
- For libraries or external dependencies, mention their usage and purpose in comments.

## Mina preferenser
- Jag vill att du svarar på svenska i så god utsträckning som möjligt.
- När du skriver text i exempelvis vyer, vill jag att du alltid utreder om vi har resurshantering (vilket oftast är fallet), så leta rätt om det finns någon .resx-fil som innehåller den texten, och använd i så fall den istället för att hårdkoda texten i vyn. När du väl är där, .resx filen, så vill jag att du först utreder om texten finns. Om den gör det återanvänd den, om inte så gör en ny nyckel i resx-filen och använd den. Det är viktigt att vi inte hårdkodar text i våra vyer, utan att vi alltid använder resurshantering för att möjliggöra enklare översättning och underhåll av texten i framtiden. När du väl implementerar texten, vill jag att du kollar på vad .resx-filen heter. Låt säga att den heter Translations.resx så vill jag att du i vyn använder den med @Translations.NyskapadNyckel för att kunna få kompileringsstöd. Jag vill också att du kollar igenom så att alla supporterade språk översätts. Låt säga att vi har svenska och engelska, vill jag att du uppdaterar värdena i båda filerna. 

## Feedback efter kodleverans
  - När du har presenterat kod, gjort ändringar i filer, eller levererat
  en lösning som användaren förväntas testa eller verifiera, använd
  alltid `ask questions`-tool/verktyget för att fråga: "Fungerade det som
  förväntat?" (eller liknande kontextanpassad fråga). Vänta på svaret
  innan du fortsätter.

## Kodstil
- Jag vill att du skriver kod/kommentarer i så stor utsträckning som möjligt på engelska. I dom fall där översättningar till engelska inte känns intuitiva vill jag att du skriver på svenska.

## Skills
- Utvärdera om jag har några skills installerade som är specialiserade på det jag efterfrågar, och i så fall använd dessa för att ge mer precisa och relevanta svar.
