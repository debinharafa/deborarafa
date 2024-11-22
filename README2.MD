# Documentação do Componente `Navbar`

## Descrição
O componente `Navbar` exibe uma barra de navegação simples com o título "Ristorante Con Fusion" e uma mensagem de autoria: **Aluno: Debora Rafaelle**.

---

## Estrutura do Componente

1. **`<Navbar>`**: 
   - Barra de navegação com tema escuro e cor azul.
   
2. **`<NavbarBrand>`**: 
   - Título principal "Ristorante Con Fusion", com link para a página inicial.

3. **`<div>` (Aluno)**: 
   - Exibe o texto "Aluno: Debora Rafaelle".

---
imagem do resultado do exercicio:

![alt text](<Captura de tela 2024-11-21 205524.png>)
## Código Fonte

```jsx
<Navbar dark color="primary">
  <div className="container">
    <NavbarBrand href="/">Ristorante Con Fusion</NavbarBrand>
    <div>Aluno: Debora Rafaelle</div>
  </div>
</Navbar>
Estilo e Funcionalidades
Cor e Tema:
Fundo azul e texto branco, configurados com color="primary" e dark.
Layout Responsivo:
Centralização do conteúdo com a classe container.
Requisitos
Instalar o Bootstrap no projeto:
bash
Copiar código
npm install bootstrap
Importar os estilos no arquivo principal:
javascript
Copiar código
import 'bootstrap/dist/css/bootstrap.min.css';
 
 