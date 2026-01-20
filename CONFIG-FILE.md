## 📊 PODSUMOWANIE ANALIZY REPOZYTORIUM

**Typ projektu:** Sklep e-commerce PrestaShop dla narzędzi BHP  
**Stack technologiczny:** PHP 85.2%, JavaScript 14.8%, CSS, HTML  
**Framework CMS:** PrestaShop (wersja premium theme w `/src`)  
**Branża:** Narzędzia elektryczne i BHP (podobne do Wiha Tools)  
**Rynek docelowy:** Polska (język polski)  
**Istniejące katalogi:** `.claude-plugin/`, `.claude/`, `.github/`, `agents/`, `collections/`, `docs/`, `eng/`, `instructions/`, `prompts/`, `src/`

**Kluczowe wymagania:**

- Integracje: InPost, DPD, PayU, Przelewy24, tawk.to, SubiektGT, Allegro
- Marketing: Google Analytics, Tag Manager, Merchant Center, Ceneo, Facebook Business Suite
- SEO: OpenGraph, structured data, PageSpeed optimization
- Kolorystyka premium: primary `#8B0000`, secondary `#606060`, background `#f1f1f1`

---

## 📋 KOMPLETNA LISTA PLIKÓW DO WYGENEROWANIA

### 🎯 PRIORYTET NAJWYŻSZY - Dokumentacja dla AI

1. **AGENTS.md** - Szczegółowy opis agentów AI, ich ról i zachowań w projekcie PrestaShop
2. **CLAUDE.md** - Instrukcje dla Claude AI Projects specyficzne dla e-commerce
3. **OLLAMA.md** - Konfiguracja i instrukcje dla Ollama AI
4. **QWEN.md** - Instrukcje dla Qwen AI Desktop
5. **AI_PROMPTS.md** - Zbiór gotowych promptów dla różnych zadań (kod, SEO, content)
6. **AI_INSTRUCTIONS.md** - Instrukcje operacyjne dla wszystkich AI assistentów
7. **.claude/instructions.md** - Kontekstowe instrukcje dla Claude w projekcie
8. **copilot-instructions.md** - Instrukcje dla GitHub Copilot
9. **.cursorrules** - Reguły dla Cursor IDE
10. **.copilot/instructions.md** - Zaawansowane instrukcje Copilot

### 🚀 PRIORYTET NAJWYŻSZY - GitHub Actions Workflows

11. **.github/workflows/ci.yml** - Continuous Integration (PHP tests, JS linting)
12. **.github/workflows/prestashop-quality.yml** - Walidacja kodu PrestaShop
13. **.github/workflows/deploy-production.yml** - Deployment na produkcję
14. **.github/workflows/deploy-staging.yml** - Deployment na staging
15. **.github/workflows/security-scan.yml** - Skanowanie bezpieczeństwa (SonarQube, OWASP)
16. **.github/workflows/lighthouse-seo.yml** - Testy Lighthouse i SEO
17. **.github/workflows/backup.yml** - Automatyczne backupy bazy danych
18. **.github/workflows/dependabot-auto-merge.yml** - Auto-merge bezpiecznych zależności
19. **.github/workflows/code-review.yml** - Automatyczna code review z AI
20. **.github/workflows/prestashop-module-validator.yml** - Walidacja modułów PrestaShop

### 📚 PRIORYTET WYSOKI - Dokumentacja projektowa

21. **docs/ARCHITECTURE.md** - Architektura systemu PrestaShop
22. **docs/BRAND-SETTINGS.md** - Ustawienia brandu (kolory, fonty, logo)
23. **docs/DESIGN-SYSTEM.md** - System designu i komponenty UI
24. **docs/SEO-STRATEGY.md** - Strategia SEO dla sklepu
25. **docs/ROADMAP.md** - Plan rozwoju projektu
26. **docs/API-DOCUMENTATION.md** - Dokumentacja API i webhooków
27. **docs/INTEGRATIONS.md** - Szczegóły wszystkich integracji
28. **docs/DATABASE-SCHEMA.md** - Schemat bazy danych
29. **docs/DEPLOYMENT.md** - Procedury wdrożeniowe
30. **docs/TROUBLESHOOTING.md** - Rozwiązywanie problemów
31. **README.agents.md** - Dokumentacja agentów AI
32. **README.collections.md** - Dokumentacja kolekcji snippetów
33. **README.instructions.md** - Przewodnik po instrukcjach
34. **README.prompts.md** - Katalog promptów
35. **README.skills.md** - Dokumentacja skillsów MCP
36. **CONTRIBUTING.md** - Wytyczne dla kontrybutorów
37. **CODE_OF_CONDUCT.md** - Kodeks postępowania
38. **SECURITY.md** - Polityka bezpieczeństwa
39. **CHANGELOG.md** - Historia zmian

### 🧪 PRIORYTET WYSOKI - Pre-commit hooks i testy

40. **.pre-commit-config.yaml** - Konfiguracja pre-commit hooks
41. **.github/workflows/pre-commit.yml** - Workflow pre-commit w CI
42. **phpunit.xml** - Konfiguracja PHPUnit dla testów PHP
43. **tests/Unit/ExampleTest.php** - Przykładowy test jednostkowy
44. **tests/Integration/ModuleTest.php** - Test integracyjny modułu
45. **tests/E2E/CheckoutTest.php** - Test E2E procesu zakupowego
46. **jest.config.js** - Konfiguracja testów JavaScript
47. **tests/Frontend/cart.test.js** - Testy frontendu koszyka
48. **.github/workflows/phpunit.yml** - Workflow testów PHPUnit
49. **.github/workflows/playwright.yml** - Testy E2E Playwright

### ⚙️ Pliki konfiguracyjne środowiska

50. **.env.example** - Przykładowa konfiguracja środowiska
51. **.env.production.example** - Konfiguracja produkcyjna
52. **config/config.yml** - Główna konfiguracja aplikacji
53. **docker-compose.yml** - Środowisko Docker dla developmentu
54. **docker-compose.production.yml** - Docker dla produkcji
55. **Dockerfile** - Definicja kontenera aplikacji
56. **Dockerfile.nginx** - Definicja kontenera Nginx
57. **.dockerignore** - Ignorowane pliki w Docker
58. **nginx/prestashop.conf** - Konfiguracja Nginx dla PrestaShop
59. **nginx/ssl.conf** - Konfiguracja SSL
60. **php/php.ini** - Konfiguracja PHP
61. **php/php-fpm.conf** - Konfiguracja PHP-FPM

### 🛠️ Pliki konfiguracyjne narzędzi

62. **.editorconfig** - Konfiguracja edytora
63. **.eslintrc.js** - Linting JavaScript
64. **.prettierrc.json** - Formatowanie kodu
65. **.stylelintrc.json** - Linting CSS/SCSS
66. **.php-cs-fixer.dist.php** - Formatowanie PHP
67. **phpstan.neon** - Statyczna analiza PHP
68. **psalm.xml** - Psalm analiza PHP
69. **.gitattributes** - Atrybuty Git (aktualizacja)
70. **.gitignore** - Ignorowane pliki Git (rozszerzenie)
71. **composer.json** - Zależności PHP (jeśli brakuje)
72. **package.json** - Zależności JavaScript
73. **.nvmrc** - Wersja Node.js
74. **.php-version** - Wersja PHP

### 🔒 Pliki bezpieczeństwa i compliance

75. **.github/dependabot.yml** - Konfiguracja Dependabot
76. **.github/CODEOWNERS** - Właściciele kodu
77. **.snyk** - Konfiguracja Snyk security
78. **sonar-project.properties** - SonarQube
79. **security.txt** - RFC 9116 security contact
80. **LICENSE** - Licencja projektu
81. **.htaccess.security** - Dodatkowe zasady bezpieczeństwa
82. **robots.txt** - Instrukcje dla robotów
83. **sitemap.xml.php** - Generator mapy witryny

### 📱 Pliki SEO i Marketing

84. **templates/meta-tags-template.html** - Szablon meta tagów
85. **templates/schema-org-product.json** - Structured data produktu
86. **templates/schema-org-organization.json** - Structured data firmy
87. **templates/og-image-template.html** - Szablon OpenGraph
88. **config/google-tag-manager.js** - Konfiguracja GTM
89. **config/google-analytics.js** - Konfiguracja GA4
90. **config/facebook-pixel.js** - Facebook Pixel
91. **config/ceneo-feed.xml.php** - Feed dla Ceneo
92. **config/google-merchant-feed.xml.php** - Feed Google Merchant

### 📦 Struktura MCP i AI Agents

93. **mcp.json** - Główna konfiguracja MCP
94. **.github/mcp/registry.json** - Rejestr MCP serwerów
95. **.github/agents/prestashop-dev.json** - Agent rozwoju PrestaShop
96. **.github/agents/seo-specialist.json** - Agent SEO
97. **.github/agents/frontend-designer.json** - Agent frontend
98. **.github/agents/integration-expert.json** - Agent integracji
99. **.github/chatmodes/development.json** - Tryb development chat
100. **.github/chatmodes/production-support.json** - Tryb production support
101. **.github/knowledge/prestashop-best-practices.md** - Wiedza PrestaShop
102. **.github/knowledge/php-patterns.md** - Wzorce PHP
103. **.github/prompt-snippets/module-generator.md** - Snippet generowania modułów
104. **.github/prompt-snippets/seo-optimizer.md** - Snippet optymalizacji SEO

### 📝 Skrypty automatyzacji

105. **scripts/setup.sh** - Setup środowiska
106. **scripts/deploy.sh** - Deployment
107. **scripts/backup-database.sh** - Backup bazy danych
108. **scripts/restore-database.sh** - Restore bazy danych
109. **scripts/clear-cache.sh** - Czyszczenie cache
110. **scripts/generate-sitemap.sh** - Generowanie sitemapy
111. **scripts/optimize-images.sh** - Optymalizacja obrazków
112. **scripts/run-tests.sh** - Uruchamianie testów
113. **Makefile** - Zadania make dla projektu

### 📂 Strukturalne pliki pomocnicze

114. **collections/prestashop-snippets.json** - Snippety kodu PrestaShop
115. **collections/css-components.json** - Komponenty CSS
116. **collections/javascript-utilities.json** - Utilities JavaScript
117. **templates/blog-post-template.md** - Szablon wpisu blogowego
118. **templates/product-description-template.md** - Szablon opisu produktu
119. **templates/email-template.html** - Szablon emaila
120. **.vscode/settings.json** - Ustawienia VS Code
121. **.vscode/extensions.json** - Zalecane rozszerzenia VS Code
122. **.vscode/launch.json** - Konfiguracja debugowania
123. **.vscode/tasks.json** - Zadania VS Code
124. **.schemas/product-schema.json** - JSON schema produktu
125. **.schemas/order-schema.json** - JSON schema zamówienia

### 🎨 Pliki designu i brandingu

126. **eng/brand-guidelines.md** - Wytyczne brandowe (EN)
127. **eng/ui-components.md** - Dokumentacja komponentów UI (EN)
128. **docs/MENU-STRUCTURE.md** - Struktura menu strony
129. **docs/PRODUCT-CATEGORIES.md** - Kategorie produktów
130. **docs/COLOR-PALETTE.md** - Paleta kolorów (rozszerzenie KOLORYSTYKA)
