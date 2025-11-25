# 🎨 @priscilamouracodestudio-creator/design-tokens

Este repositório contém os **Design Tokens** centrais do nosso sistema. 
Eles garantem consistência de design (cores, espaçamento, tipografia) em todas as aplicações (Web, Mobile, etc.).

Os tokens são gerados a partir do arquivo fonte **`tokens.json`** utilizando a ferramenta **Style Dictionary**.

---

## 📦 Instalação e Uso

### 1. Instalação via NPM

Para instalar e usar os tokens no seu projeto:

```bash
npm install @priscilamouracodestudio-creator/design-tokens
```
### 2. Uso nos Projetos

#### A. Web (CSS)

Importe o arquivo `tokens.css` gerado em seu projeto web.

```css
@import '@priscilamouracodestudio-creator/design-tokens/build/css/tokens.css';

/* Exemplo de uso de uma variável de cor */
.card {
  background-color: var(--color-background-default);
  padding: var(--spacing-medium);
}
```
#### B. JavaScript/Frameworks

Importe as constantes no seu código JavaScript.

```javascript
import { ColorWhite } from '@priscilamouracodestudio-creator/design-tokens/build/js/tokens.js';

function MeuComponente() {
  const corDeFundo = ColorWhite;
  // ...
}
```
"Teste de Push Final" 
