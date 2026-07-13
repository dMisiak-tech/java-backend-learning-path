# 🗺️ Roadmap Java Backend Developer 2026 (Junior)

Kompletny, nowoczesny i niezwykle szczegółowy plan nauki przygotowany pod wymagania rynku pracy w **2026 roku**. Zaprojektowany z myślą o osobach poszukujących pierwszej pracy (Junior / Entry-level) bez komercyjnego doświadczenia.

---

## 📌 Spis Treści
1. [Moduł 1: Nowoczesny Język Java (Fundament)](#-moduł-1-nowoczesny-język-java-fundament)
2. [Moduł 2: Ekosystem i Warsztat Pracy (Narzędziownik)](#-moduł-2-ekosystem-i-warsztat-pracy-narzędziownik)
3. [Moduł 3: Relacyjne i Nierelacyjne Bazy Danych](#-moduł-3-relacyjne-i-nierelacyjne-bazy-danych)
4. [Moduł 4: Web Development – Protokół HTTP i REST API](#-moduł-4-web-development--protokół-http-i-rest-api)
5. [Moduł 5: Standard Branżowy – Spring Boot 3.x](#-moduł-5-standard-branżowy--spring-boot-3x)
6. [Moduł 6: Testowanie Aplikacji (Klucz do Sukcesu)](#-moduł-6-testowanie-aplikacji-klucz-do-sukcesu)
7. [Moduł 7: Architektura, Narzędzia Cloud i DevOps](#-moduł-7-architektura-narzędzia-cloud-i-devops)
8. [Moduł 8: Efektywne Wykorzystanie AI w Pracy Dewelopera](#-moduł-8-efektywne-wykorzystanie-ai-w-pracy-dewelopera)
9. [🚀 Twój Projekt Pokazowy (Showcase Project 2026)](#-twój-projekt-pokazowy-showcase-project-2026)

---

## ☕ Moduł 1: Nowoczesny Język Java (Fundament)
W 2026 roku standardem w nowych projektach komercyjnych są wersje LTS: **Java 17** oraz **Java 21** (oraz przygotowanie pod Java 25). Unikaj materiałów opartych wyłącznie o starą Javę 8.

### 🟩 Podstawy języka i OOP (Object-Oriented Programming)
- [ ] **Paradygmaty OOP:** Abstrakcja, Enkapsulacja, Dziedziczenie, Polimorfizm (musisz znać przykłady użycia w kodzie).
- [ ] **Klasy i Interfejsy:** Różnice, zastosowanie klas abstrakcyjnych vs interfejsów (w tym metody domyślne `default` i prywatne w interfejsach).
- [ ] **Typy danych:** Typy prymitywne vs referencyjne, mechanizm Autoboxingu i Unboxingu.
- [ ] **Obsługa wyjątków (Exception Handling):** Wyjątki kontrolowane (*checked*) vs niekontrolowane (*unchecked*), hierarchia klasy `Throwable`, blok `try-catch-finally` oraz struktura `try-with-resources`.

### 🟦 Zaawansowane mechanizmy Javy
- [ ] **Java Collections Framework (JCF):**
  - Znajomość i zastosowanie: `List` (`ArrayList`, `LinkedList`), `Set` (`HashSet`, `TreeSet`), `Map` (`HashMap`, `TreeMap`).
  - Złożoność obliczeniowa (Big O) podstawowych operacji na tych strukturach.
  - Jak działa `HashMap` pod spodem (kubełki, kolizje, kontrakt `equals()` i `hashCode()`).
- [ ] **Generyki (Generics):** Typowanie generyczne, metody generyczne, mechanizmy *bounded wildcards* (`? extends T`, `? super T`).
- [ ] **Programowanie funkcyjne (Java 8+):**
  - Wbudowane interfejsy funkcjonalne: `Predicate`, `Consumer`, `Supplier`, `Function`.
  - Wyrażenia Lambda oraz referencje do metod (np. `String::toUpperCase`).
  - **Stream API:** Przetwarzanie potokowe danych (`filter`, `map`, `flatMap`, `reduce`, `collect`).
- [ ] **Klasa `Optional`:** Bezpieczna obsługa wartości mogących być nullem.

### 🟪 Nowości w Java 11, 17, 21 (Pytania rekrutacyjne)
- [ ] **Rekordy (`records`):** Niemutowalne klasy danych redukujące boilerplate code.
- [ ] **Klasy zapieczętowane (`sealed classes/interfaces`):** Kontrola nad hierarchią dziedziczenia.
- [ ] **Pattern Matching:** Dopasowanie do wzorców dla instrukcji `switch` oraz operatora `instanceof`.
- [ ] **Wirtualne Wątki (Virtual Threads - Project Loom):** Rewolucja w współbieżności Javy 21. Musisz rozumieć różnicę między wątkami platformowymi (systemowymi) a wirtualnymi.

---

## 🛠️ Moduł 2: Ekosystem i Warsztat Pracy (Narzędziownik)
Narzędzia niezbędne do pracy w każdym zespole programistycznym.

- [ ] **System Kontroli Wersji Git & GitHub:**
  - Codzienne operacje: `commit`, `push`, `pull`, `fetch`.
  - Praca na gałęziach: `checkout -b`, `merge`, `rebase`, `stash`, `cherry-pick`.
  - Przepływy pracy: *Gitflow* oraz *Trunk-Based Development*.
  - Code Review: Tworzenie Pull Requestów (PR) zgodnie z konwencją *Conventional Commits*.
- [ ] **Narzędzia Budowania:** **Maven** oraz **Gradle** (struktura katalogów, pliki `pom.xml` / `build.gradle`, cykl życia budowania, zarządzanie zależnościami).
- [ ] **SDKMAN!:** Wygodne zarządzanie i przełączanie wersji JDK oraz narzędzi deweloperskich.
- [ ] **IDE:** IntelliJ IDEA (skróty klawiszowe, uruchamianie testów, debugowanie kodu krok po kroku).

---

## 💾 Moduł 3: Relacyjne i Nierelacyjne Bazy Danych

### 🛢️ Relacyjne Bazy Danych (RDBMS) – PostgreSQL / MySQL
- [ ] **Projektowanie baz danych:** Normalizacja tabel (1NF, 2NF, 3NF), relacje (`1:1`, `1:N`, `N:M`).
- [ ] **Język SQL:**
  - DDL (Data Definition Language): `CREATE`, `ALTER`, `DROP`.
  - DML (Data Manipulation Language): `SELECT`, `INSERT`, `UPDATE`, `DELETE`.
  - Agregacje i złączenia: `JOIN` (INNER, LEFT, RIGHT), `GROUP BY`, `HAVING`.
- [ ] **Optymalizacja i Bezpieczeństwo:** Transakcje (właściwości ACID), poziomy izolacji transakcji, tworzenie i działanie indeksów.

### ☕ JPA & Hibernate (Object-Relational Mapping)
- [ ] **Mapowanie obiektowo-relacyjne:** Koncepcja ORM, adnotacje `@Entity`, `@Table`, `@Id`.
- [ ] **Modelowanie relacji:** `@OneToOne`, `@OneToMany`, `@ManyToOne`, `@ManyToMany`.
- [ ] **Cykl życia encji:** Stany *Transient*, *Managed*, *Detached*, *Removed*.
- [ ] **Problem wydajnościowy N+1 zapytań:** Czym jest i jak go rozwiązać (użycie `JOIN FETCH`, `@EntityGraph` lub dedykowanych zapytań JPQL).
- [ ] **Mechanizmy ładowania:** Leniwe ładowanie (*Lazy*) vs Natychmiastowe (*Eager*).

### ⚡ Bazy Nierelacyjne (NoSQL) – Podstawy
- [ ] **Redis:** Wykorzystanie jako pamięć podręczna (Cache Key-Value) do przyspieszenia odczytu z bazy relacyjnej.

---

## 🌐 Moduł 4: Web Development – Protokół HTTP i REST API

- [ ] **Protokół HTTP/HTTPS:** Struktura żądania (Request) i odpowiedzi (Response), nagłówki, ciasteczka, sesje.
- [ ] **Metody HTTP:** Różnice i idempotentność dla `GET`, `POST`, `PUT`, `PATCH`, `DELETE`.
- [ ] **Kody statusów HTTP:** Popularne kody z grup 2xx, 3xx, 4xx oraz 5xx.
- [ ] **Zasady projektowania RESTful API:** Spójne nazewnictwo punktów końcowych (Endpoints), bezstanowość (Stateless), przesyłanie danych w formacie JSON.

---

## 🍃 Moduł 5: Standard Branżowy – Spring Boot 3.x
Spring Boot 3.x oparty o Spring Framework 6 to absolutne jądro backendu w świecie Javy.

### 🌱 1. Spring Core
- [ ] **Wstrzykiwanie zależności (DI) & Odwrócenie sterowania (IoC):** Zrozumienie idei luźnego powiązania (loose coupling).
- [ ] **Zarządzanie Beanami:** Adnotacje `@Component`, `@Service`, `@Repository`, `@Configuration`, `@Bean`.
- [ ] **Cykl życia Beana:** Zastosowanie `@PostConstruct` oraz `@PreDestroy`.
- [ ] **Wstrzykiwanie zależności:** Dlaczego należy używać wstrzykiwania przez konstruktor zamiast `@Autowired` na polach.
- [ ] **Profile Springa:** Zarządzanie konfiguracją środowiskową (`application-dev.yml`, `application-prod.yml`).

### 🌐 2. Spring Web
- [ ] **REST Kontrolery:** Adnotacja `@RestController`, `@RequestMapping`, `@GetMapping`, `@PostMapping` itp.
- [ ] **Przekazywanie danych:** `@PathVariable`, `@RequestParam`, `@RequestBody`.
- [ ] **Walidacja danych:** Użycie adnotacji z `jakarta.validation.constraints` (`@NotNull`, `@Size`, `@Email`).
- [ ] **Globalna obsługa błędów:** Obsługa wyjątków za pomocą `@RestControllerAdvice` i `@ExceptionHandler`.

### 📊 3. Spring Data JPA
- [ ] **Repozytoria:** Korzystanie z interfejsu `JpaRepository`.
- [ ] **Query Methods:** Generowanie zapytań na podstawie nazw metod w interfejsie.
- [ ] **Zapytania własne:** Pisanie zapytań JPQL oraz SQL natywnego przy użyciu adnotacji `@Query`.

### 🔒 4. Spring Security & JWT (Standard 2026)
- [ ] **Uwierzytelnianie vs Autoryzacja:** Podstawowe różnice koncepcyjne.
- [ ] **Konfiguracja bezpieczeństwa:** Definiowanie niestandardowego `SecurityFilterChain`.
- [ ] **JSON Web Token (JWT):** Bezstanowa autoryzacja żądań na podstawie tokenów JWT.
- [ ] **Ochrona przed podatnościami:** Podstawowa ochrona przed SQL Injection, Cross-Site Scripting (XSS) oraz CSRF.

---

## 🧪 Moduł 6: Testowanie Aplikacji (Klucz do Sukcesu)
Umiejętność pisania solidnych testów automatycznych to główny wyróżnik świetnego Juniora.

- [ ] **Testy Jednostkowe (Unit Tests):**
  - Framework **JUnit 5** oraz biblioteka asercji płynnych **AssertJ**.
  - **Mockito:** Mockowanie zewnętrznych zależności za pomocą `@Mock`, `@InjectMocks`, `when().thenReturn()`, `verify()`.
- [ ] **Testy Integracyjne (Integration Tests):**
  - Narzędzia Springa: `@SpringBootTest`, `@ActiveProfiles`.
  - **Testcontainers:** Nowoczesny standard uruchamiania prawdziwej bazy danych (np. PostgreSQL) lub serwisu trzeciego (np. Redis) w kontenerach Docker na czas trwania testów.

---

## 🐳 Moduł 7: Architektura, Narzędzia Cloud i DevOps

- [ ] **Architektura Aplikacji:**
  - Podział na warstwy: *Controller* (prezentacja) -> *Service* (logika biznesowa) -> *Repository* (dostęp do danych).
  - Praktyki czystego kodu: Zasady **SOLID**, **DRY** (Don't Repeat Yourself) oraz **KISS** (Keep It Simple, Stupid).
  - Mapowanie danych: Rozdzielenie obiektów bazodanowych od obiektów API za pomocą biblioteki **MapStruct** (DTO Pattern).
- [ ] **Docker (Konteneryzacja):**
  - Zrozumienie pojęć: obraz vs kontener.
  - Tworzenie własnych plików `Dockerfile` dla aplikacji Spring Boot.
  - Narzędzie **Docker Compose** do uruchamiania całej infrastruktury lokalnie (`docker-compose.yml` wiążący aplikację z bazą PostgreSQL).
- [ ] **CI/CD:** Podstawy automatyzacji budowania i testowania kodu za pomocą **GitHub Actions**.

---

## 🤖 Moduł 8: Efektywne Wykorzystanie AI w Pracy Dewelopera
W 2026 roku deweloperzy nie konkurują z AI, lecz z innymi programistami korzystającymi z AI.

- [ ] **Wsparcie w pisaniu kodu:** Praca z asystentami takimi jak GitHub Copilot czy czaty LLM.
- [ ] **Krytyczne myślenie:** Umiejętność weryfikacji kodu wygenerowanego przez AI pod kątem optymalności, podatności na błędy bezpieczeństwa oraz zgodności z architekturą projektu.
- [ ] **Generowanie testów:** Wykorzystanie AI do szybkiego pisania kodu boilerplate w testach jednostkowych.

---

## 🚀 Twój Projekt Pokazowy (Showcase Project 2026)
Nie twórz kolejnej prostej aplikacji "To-Do". Aby zdobyć pierwszą pracę, stwórz **jeden zaawansowany system** (np. system rezerwacji biletów kinowych, platformę mikropożyczek lub moduł e-commerce), który będzie zawierać:

1. **Architekturę wielowarstwową** z wykorzystaniem DTO (`MapStruct`).
2. **Pełne bezpieczeństwo** oparte o Spring Security i JWT.
3. **Kompletne pokrycie testami:** testy jednostkowe (`JUnit 5`, `Mockito`) oraz integracyjne z użyciem bazy PostgreSQL uruchamianej przez `Testcontainers`.
4. **Konteneryzację:** plik `Dockerfile` oraz `docker-compose.yml` umożliwiający uruchomienie całego środowiska jednym poleceniem.
5. **Profesjonalne repozytorium GitHub:** Regularna historia czytelnych commitów, gałęzie funkcjonalne (feature branches) oraz dopracowany plik `README.md` z opisem działania projektu i instrukcją uruchomienia.

---
*Powodzenia! Systematyczna realizacja tej mapy drogowej krok po kroku gwarantuje przygotowanie na najwyższym poziomie do rekrutacji na stanowisko Junior Java Backend Developer.*
