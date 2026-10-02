# Anderson Júnior — Portfólio Profissional

Portfólio pessoal responsivo de **Anderson Júnior Cardoso Silva**, estudante de Engenharia de Software com experiência em suporte técnico, documentação e processos administrativos.

O projeto foi desenvolvido para apresentar a trajetória profissional, competências técnicas, formação acadêmica e projetos pessoais de forma clara para recrutadores.

## Preview

[Visualizar o portfólio](https://andersonfoli-vhdfmgmp.manus.space/)

## Objetivos

- Apresentar o perfil profissional de forma objetiva e escaneável.
- Destacar experiência real em suporte de TI.
- Demonstrar conhecimentos em desenvolvimento web.
- Reunir projetos, formação e canais de contato em uma única página.
- Servir como base para publicação no GitHub Pages ou outro serviço de hospedagem estática.

## Tecnologias

- **HTML5 semântico**
- **CSS3**
- **JavaScript puro**
- **Node.js** para o servidor local de preview
- **Git e GitHub**
- **Google Fonts** — Inter e IBM Plex Mono

## Funcionalidades

- Layout responsivo para desktop, tablet e celular.
- Navegação por âncoras entre as seções da página.
- Menu mobile expansível.
- Animações discretas de entrada durante a rolagem.
- Suporte à preferência `prefers-reduced-motion`.
- Links para e-mail, LinkedIn, GitHub e telefone.
- Cards de experiência, habilidades, projetos e formação.
- Favicon e identidade visual própria.
- Metadados básicos para SEO e compartilhamento social.
- Manifesto de rotas em `manus-routes.json`.
- Arquivo `robots.txt` configurado para rastreamento público.

## Estrutura do projeto

```text
.
├── index.html          # Página principal do portfólio
├── styles.css          # Estilos, layout e responsividade
├── script.js           # Menu mobile, animações e ano do rodapé
├── server.js           # Servidor estático local para preview
├── package.json        # Configuração e comando de execução
├── favicon.svg         # Ícone do navegador
├── logo.png            # Logo quadrada do projeto
├── app.config.ts       # Metadata da logo para o Web Dev
├── manus-routes.json   # Manifesto das rotas públicas
├── robots.txt          # Diretrizes básicas para crawlers
└── ideas.md            # Direção visual e princípios de design
```

## Como executar localmente

### Pré-requisitos

- Node.js 18 ou superior
- npm ou pnpm

### Inicialização

Clone o repositório e entre na pasta do projeto:

```bash
git clone <url-do-repositorio>
cd andersonfolio
```

Inicie o servidor local:

```bash
npm start
```

O site ficará disponível em:

```text
http://localhost:3000
```

O projeto não possui dependências externas de runtime. O servidor usa apenas módulos nativos do Node.js.

## Personalização

As informações principais ficam diretamente no arquivo `index.html`:

- Nome e apresentação profissional.
- Experiências profissionais.
- Habilidades e níveis de familiaridade.
- Projetos.
- Formação e cursos.
- Links de contato.

Para alterar a identidade visual, edite as variáveis de cor no início de `styles.css`:

```css
:root {
  --bg: #0b111a;
  --surface: #121d2a;
  --blue: #71b7ff;
  --green: #9fe870;
}
```

Para adicionar um novo projeto, inclua um novo `article` na seção `#projetos` e mantenha as tags de tecnologia consistentes com os cards existentes.

## Boas práticas adotadas

- HTML semântico e hierarquia clara de títulos.
- Link para pular diretamente ao conteúdo principal.
- Foco visível para navegação por teclado.
- Contraste adequado entre texto e fundo.
- Uso de `rel="noopener noreferrer"` em links externos abertos em nova aba.
- Animações desativadas quando o usuário prefere movimento reduzido.
- Descrições profissionais sem inventar métricas ou qualificações.
- Conteúdo inicial disponível diretamente no HTML, favorecendo SEO.

## Verificações

As verificações realizadas incluem:

```bash
node --check server.js
node --check script.js
```

Também foram validados:

- Resposta HTTP da página principal.
- Resposta HTTP de `manus-routes.json`.
- Resposta HTTP de `robots.txt`.
- Presença das descrições dos projetos e metadados SEO.
- Funcionamento do preview local e público.

## Próximos passos sugeridos

- Criar uma aplicação de lista de tarefas completa com JavaScript e LocalStorage.
- Adicionar links diretos para repositórios específicos de cada projeto.
- Incluir certificados com instituição, carga horária e ano de conclusão.
- Adicionar uma versão em inglês do portfólio.
- Publicar uma versão permanente em um domínio próprio ou GitHub Pages.

## Contato

- **E-mail:** [anderson.junsilva@gmail.com](mailto:anderson.junsilva@gmail.com)
- **LinkedIn:** [linkedin.com/in/juniosilvaw](https://linkedin.com/in/juniosilvaw)
- **GitHub:** [github.com/juniosilvaw](https://github.com/juniosilvaw)
- **Telefone:** [+55 31 9 7358-2158](tel:+5531973582158)

## Licença

Este projeto é um portfólio pessoal. O código pode ser utilizado como referência para estudos, desde que o conteúdo, a identidade e os dados pessoais de Anderson Júnior não sejam reutilizados como se fossem de outra pessoa.
