# AI Coding Assistant Guide for Pi Explorer

*Przewodnik asystenta kodowania AI dla Pi Explorer*

## English

### What can AI coding assistants do to help with this project?

AI coding assistants like GitHub Copilot, ChatGPT, Claude, and similar tools can significantly accelerate development on the Pi Explorer blockchain explorer. Here are specific ways they can help:

#### 1. **React Component Development**
- **Auto-complete React components**: Get intelligent suggestions for JSX, props, and component structure
- **State management**: Help with React hooks, state updates, and component lifecycle
- **Event handlers**: Generate boilerplate for click handlers, form submissions, and user interactions

**Example uses in this project:**
```javascript
// AI can help complete components like SearchBox, PaymentTable, etc.
const SearchBox = () => {
  const [searchStr, setSearchStr] = useState('');
  // AI suggests proper event handlers and validation
}
```

#### 2. **Blockchain Data Handling**
- **API integration**: Help with Stellar SDK usage and blockchain API calls
- **Data parsing**: Convert blockchain data into displayable formats
- **Transaction validation**: Generate code for validating addresses, transaction hashes, etc.

**Example uses:**
```javascript
// AI can help with stellar-sdk operations
import { Server } from 'stellar-sdk';
// AI suggests proper error handling and data transformation
```

#### 3. **Testing and Quality Assurance**
- **Test generation**: Create unit tests for React components
- **Mock data**: Generate realistic test data for blockchain transactions
- **Error handling**: Suggest comprehensive error handling patterns

#### 4. **Internationalization (i18n)**
- **Translation keys**: Generate consistent translation key structures
- **Message formatting**: Help with React Intl message formatting
- **Language file maintenance**: Suggest missing translations or inconsistencies

**Current supported languages in this project:**
- English (en)
- French (fr)
- Hindi (hi)
- Indonesian (id)
- Italian (it)
- Japanese (ja)
- Nepali (ne)
- Portuguese (pt)
- Russian (ru)
- Urdu (ur)
- Vietnamese (vi)
- Chinese Simplified (zh-Hans)
- Chinese Traditional (zh-Hant)
- Hausa (hau)

#### 5. **Code Modernization**
This project uses older React patterns. AI can help with:
- Converting class components to functional components with hooks
- Updating deprecated dependencies
- Implementing modern React patterns
- Performance optimizations

#### 6. **Documentation**
- **API documentation**: Generate JSDoc comments
- **README improvements**: Suggest documentation enhancements
- **Code comments**: Add helpful inline documentation

### How to use AI assistants effectively with this project:

1. **Be specific about the context**: Mention you're working with a React blockchain explorer
2. **Include relevant imports**: Show what libraries you're using (stellar-sdk, react-bootstrap, etc.)
3. **Provide component structure**: Share the existing component structure for better suggestions
4. **Ask for specific patterns**: Request help with React patterns, error handling, or performance
5. **Request tests**: Always ask for corresponding tests when implementing new features

### Common prompts for this project:

- "Help me create a React component for displaying Pi Network transaction details"
- "Generate unit tests for the SearchBox component using Jest and Enzyme"
- "Convert this class component to a functional component with hooks"
- "Add error handling for Stellar API calls in this component"
- "Create translation keys for this new feature in multiple languages"
- "Help optimize this component's rendering performance"

---

## Polski

### Jak asystenci kodowania AI mogą pomóc w tym projekcie?

Asystenci kodowania AI, tacy jak GitHub Copilot, ChatGPT, Claude i podobne narzędzia, mogą znacząco przyspieszyć rozwój eksploratora blockchain Pi Explorer. Oto konkretne sposoby, w jakie mogą pomóc:

#### 1. **Tworzenie komponentów React**
- **Automatyczne uzupełnianie komponentów React**: Inteligentne sugestie dla JSX, props i struktury komponentów
- **Zarządzanie stanem**: Pomoc z hookami React, aktualizacjami stanu i cyklem życia komponentów
- **Obsługa zdarzeń**: Generowanie kodu dla obsługi kliknięć, przesyłania formularzy i interakcji użytkownika

**Przykłady zastosowania w tym projekcie:**
```javascript
// AI może pomóc uzupełnić komponenty takie jak SearchBox, PaymentTable, itp.
const SearchBox = () => {
  const [searchStr, setSearchStr] = useState('');
  // AI sugeruje odpowiednie obsługi zdarzeń i walidację
}
```

#### 2. **Obsługa danych blockchain**
- **Integracja API**: Pomoc z używaniem Stellar SDK i wywołaniami API blockchain
- **Parsowanie danych**: Konwertowanie danych blockchain do formatów do wyświetlenia
- **Walidacja transakcji**: Generowanie kodu do walidacji adresów, hashy transakcji, itp.

#### 3. **Testowanie i zapewnienie jakości**
- **Generowanie testów**: Tworzenie testów jednostkowych dla komponentów React
- **Dane testowe**: Generowanie realistycznych danych testowych dla transakcji blockchain
- **Obsługa błędów**: Sugerowanie kompleksowych wzorców obsługi błędów

#### 4. **Internacjonalizacja (i18n)**
- **Klucze tłumaczeń**: Generowanie spójnych struktur kluczy tłumaczeń
- **Formatowanie wiadomości**: Pomoc z formatowaniem wiadomości React Intl
- **Utrzymanie plików językowych**: Sugerowanie brakujących tłumaczeń lub niespójności

#### 5. **Modernizacja kodu**
Ten projekt używa starszych wzorców React. AI może pomóc z:
- Konwertowaniem komponentów klasowych na funkcyjne z hookami
- Aktualizacją przestarzałych zależności
- Implementacją nowoczesnych wzorców React
- Optymalizacją wydajności

#### 6. **Dokumentacja**
- **Dokumentacja API**: Generowanie komentarzy JSDoc
- **Ulepszenia README**: Sugerowanie ulepszeń dokumentacji
- **Komentarze kodu**: Dodawanie pomocnej dokumentacji inline

### Jak skutecznie używać asystentów AI z tym projektem:

1. **Bądź precyzyjny co do kontekstu**: Wspomniej, że pracujesz z eksploratorem blockchain React
2. **Dołącz odpowiednie importy**: Pokaż, jakich bibliotek używasz (stellar-sdk, react-bootstrap, itp.)
3. **Podaj strukturę komponentu**: Udostępnij istniejącą strukturę komponentu dla lepszych sugestii
4. **Proś o konkretne wzorce**: Poproś o pomoc ze wzorcami React, obsługą błędów lub wydajnością
5. **Proś o testy**: Zawsze proś o odpowiednie testy podczas implementacji nowych funkcji

### Typowe zapytania dla tego projektu:

- "Pomóż mi stworzyć komponent React do wyświetlania szczegółów transakcji Pi Network"
- "Wygeneruj testy jednostkowe dla komponentu SearchBox używając Jest i Enzyme"
- "Przekonwertuj ten komponent klasowy na funkcyjny z hookami"
- "Dodaj obsługę błędów dla wywołań Stellar API w tym komponencie"
- "Stwórz klucze tłumaczeń dla tej nowej funkcji w wielu językach"
- "Pomóż zoptymalizować wydajność renderowania tego komponentu"