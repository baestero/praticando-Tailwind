# 📚 Praticando Tailwind CSS

Este repositório é dedicado ao estudo e prática do **Tailwind CSS**, um framework de CSS utilitário que permite criar designs responsivos e modernos de forma eficiente.

## 🚀 Configuração do Projeto

- **Tailwind CSS v4.1.14**: Versão mais recente do framework
- **Node.js**: Gerenciamento de dependências via npm
- **Configuração personalizada**: Arquivo `tailwind.config.js` configurado para escanear todos os arquivos HTML em `src/`

## 📁 Estrutura do Projeto

```
src/
├── 001-boxModel/
│   └── boxModel.html          # Conceitos básicos do Box Model
└── 002-boxModel-desafio/
    └── boxModel-desafio.html  # Desafio prático: Layout de Curriculum
```

## 📖 Conteúdo Estudado

### 1. **Box Model Básico** (`001-boxModel/boxModel.html`)
Conceitos fundamentais abordados:
- **Cores**: `bg-gray-300`, `bg-sky-200`, `bg-yellow-400`
- **Dimensões**: `w-16`, `h-24`, `size-36`, `w-1/3`
- **Bordas**: `border-4`, `border-purple-600`
- **Margens**: `m-4`, `my-8`, `mt-4`, `pt-4`
- **Tipografia**: `text-white`, `text-sky-900`

### 2. **Desafio Prático** (`002-boxModel-desafio/boxModel-desafio.html`)
Layout de curriculum implementando:
- **Estrutura hierárquica**: Títulos e seções organizadas
- **Design consistente**: Uso de cores e espaçamentos padronizados
- **Elementos visuais**: Bordas laterais coloridas para categorização
- **Tipografia responsiva**: Diferentes tamanhos de texto (`text-2xl`, `text-sm`, `text-xs`)
- **Espaçamento sistemático**: Margens e padding bem definidos

## 🎨 Conceitos Aplicados

- **Sistema de cores**: Paleta de cinzas, roxo e azul
- **Responsividade**: Uso de frações para larguras (`w-1/3`)
- **Espaçamento**: Sistema de margin/padding do Tailwind
- **Tipografia**: Hierarquia de tamanhos e pesos de fonte
- **Bordas**: Estilização com cores e espessuras variadas

## 🛠️ Como Executar

1. Instale as dependências:
```bash
npm install
```

2. Compile o CSS:
```bash
npx tailwindcss -i ./input.css -o ./output.css --watch
```

3. Abra os arquivos HTML no navegador para visualizar os resultados

## 📈 Próximos Passos

- [ ] Flexbox e Grid Layout
- [ ] Responsividade avançada
- [ ] Componentes customizados
- [ ] Animações e transições
- [ ] Dark mode
- [ ] Pseudo-classes e estados

---

*Repositório em constante evolução para dominar o Tailwind CSS! 🎯*

