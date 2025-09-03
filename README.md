# Landing Page - Franco's Arena Beach Tennis

Uma landing page elegante para bio do Instagram da arena de beach tennis Franco's Arena, com design responsivo e cores inspiradas na praia.

## � Características

- Design responsivo (funciona em todos os dispositivos)
- Cores inspiradas em beach tennis (laranja, amarelo e verde água)
- Retângulo transparente central com efeito glass morphism
- Imagem de background de areia
- 5 links para WhatsApp (diferentes departamentos)
- 1 link para Instagram
- Link para localização no rodapé
- Animações suaves e efeitos hover

## 📱 Como personalizar

### 1. Links de WhatsApp (5 números)
No arquivo `index.html`, atualize os seguintes links:

```html
<!-- WhatsApp Reservas -->
<a href="https://wa.me/5511999999999" class="social-link whatsapp" target="_blank">

<!-- WhatsApp Aulas -->
<a href="https://wa.me/5511999999998" class="social-link whatsapp" target="_blank">

<!-- WhatsApp Eventos -->
<a href="https://wa.me/5511999999997" class="social-link whatsapp" target="_blank">

<!-- WhatsApp Administração -->
<a href="https://wa.me/5511999999996" class="social-link whatsapp" target="_blank">

<!-- WhatsApp Suporte -->
<a href="https://wa.me/5511999999995" class="social-link whatsapp" target="_blank">
```

### 2. Instagram
```html
<!-- Instagram - substitua o username -->
<a href="https://instagram.com/francosarena" class="social-link instagram" target="_blank">
```

### 3. Localização
```html
<!-- Localização - substitua o endereço -->
<a href="https://maps.google.com/?q=Franco's+Arena+Beach+Tennis" class="location-link" target="_blank">
```

### 4. Logo
- Substitua o arquivo `logo.png` pela logo real da Franco's Arena
- O design já está otimizado para logos circulares

### 5. Background
A página está configurada para usar `areia.jpg`. Para usar sua foto:
1. Adicione sua imagem de areia na pasta do projeto
2. Renomeie para `areia.jpg` ou atualize a referência no CSS

### 6. Cores
Para alterar as cores, edite o arquivo `styles.css`:

```css
/* Gradient de fundo - cores de praia */
background: linear-gradient(135deg, #f4a261 0%, #e9c46a 50%, #2a9d8f 100%);

/* Cor principal laranja */
color: #f4a261;
```

## 🚀 Como usar

1. Faça o upload dos arquivos para seu servidor web
2. Acesse através do domínio/subdomínio
3. Use o link na bio do Instagram

## 📁 Estrutura de arquivos

```
landingPageCorporius/
├── index.html      # Página principal
├── styles.css      # Estilos e layout
├── logo.png        # Logo da Franco's Arena
├── areia.jpg       # Background de areia
└── README.md       # Este arquivo
```

## 🎯 Elementos incluídos

✅ Background de areia  
✅ Retângulo transparente central  
✅ Espaço para logo  
✅ Nome "Franco's Arena Beach Tennis"  
✅ 5 links de WhatsApp (Reservas, Aulas, Eventos, Administração, Suporte)  
✅ Link do Instagram  
✅ Link de localização clicável no rodapé  
✅ Cores de beach tennis (laranja, amarelo, verde água)  
✅ Design responsivo otimizado para mobile  

## 📞 Personalização recomendada

1. **WhatsApp**: Substitua todos os números pelos reais de cada departamento
2. **Instagram**: Substitua `francosarena` pelo username real
3. **Localização**: Substitua pelo endereço real da arena
4. **Logo**: Adicione a logo oficial da Franco's Arena
5. **Background**: Use uma foto real da areia/quadras da arena
