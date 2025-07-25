# Portfólio Profissional - Magno Silva Andrade

Este é um site de portfólio profissional completo para Magno Silva Andrade, Operador de Usina Sênior especializado em Sistemas Elétricos de Potência.

## 📁 Estrutura do Projeto

```
magno_site_novo/
├── index.html                 # Página principal do site
├── style.css                  # Estilos CSS profissionais
├── script.js                  # Funcionalidades JavaScript
├── README.md                  # Este arquivo
├── 2025-07-20.png            # Foto pessoal do Magno
└── ImagemdoWhatsApp...jpg     # Certificados e diplomas (8 arquivos)
```

## 🚀 Como usar no VSCode

### 1. Preparação
1. Abra o VSCode
2. Crie uma nova pasta para o projeto
3. Copie todos os arquivos desta pasta para sua nova pasta no VSCode

### 2. Estrutura de Arquivos
Certifique-se de que todos os arquivos estejam na mesma pasta:
- `index.html` (arquivo principal)
- `style.css` (estilos)
- `script.js` (funcionalidades)
- `2025-07-20.png` (foto pessoal)
- Todos os arquivos de certificados (.jpg)

### 3. Visualização Local
1. Clique com o botão direito no arquivo `index.html`
2. Selecione "Open with Live Server" (se tiver a extensão instalada)
3. Ou simplesmente abra o arquivo no navegador

### 4. Extensões Recomendadas para VSCode
- **Live Server**: Para visualização em tempo real
- **HTML CSS Support**: Para melhor suporte HTML/CSS
- **Auto Rename Tag**: Para renomear tags automaticamente
- **Prettier**: Para formatação de código

## ✨ Funcionalidades do Site

### 🎨 Design Profissional
- Layout moderno e responsivo
- Paleta de cores azul e verde corporativa
- Tipografia profissional (Inter)
- Animações suaves e efeitos visuais

### 📱 Responsividade
- Funciona perfeitamente em desktop, tablet e mobile
- Menu hambúrguer para dispositivos móveis
- Imagens adaptáveis

### 💬 Integração WhatsApp
- Botão principal no hero da página
- Botão flutuante sempre visível
- Número (92) 99214-4163 configurado
- Mensagens automáticas personalizadas

### 🏆 Galeria de Certificados
- 8 certificados organizados em cards
- Modal lightbox para visualização ampliada
- Botões "Ver Certificado" interativos
- Imagens em orientação horizontal

### 📞 Contatos Clicáveis
- **Telefone**: Clica e direciona para ligação
- **Email**: Abre aplicativo de email (andrademagno03@gmail.com)
- **Localização**: Direciona para Google Maps (São José dos Pinhais, PR)
- **LinkedIn**: Link para perfil profissional

### ⚡ Funcionalidades Interativas
- Navegação suave entre seções
- Botão "voltar ao topo"
- Animações de entrada dos elementos
- Contador animado nas estatísticas
- Efeito parallax no hero
- Menu responsivo com animação

## 🛠️ Personalização

### Alterar Informações Pessoais
Edite o arquivo `index.html` e procure por:
- Nome: Procure por "Magno Silva Andrade"
- Telefone: Procure por "(92) 99214-4163"
- Email: Procure por "andrademagno03@gmail.com"
- LinkedIn: Procure por "linkedin.com/in/magno-andrade"

### Alterar Cores
Edite o arquivo `style.css` e modifique as variáveis CSS no `:root`:
```css
:root {
    --primary-color: #2563eb;    /* Azul principal */
    --secondary-color: #10b981;  /* Verde secundário */
    --accent-color: #3b82f6;     /* Azul de destaque */
}
```

### Adicionar/Remover Certificados
1. Adicione a imagem na pasta do projeto
2. No `index.html`, adicione um novo card na seção certificates:
```html
<div class="certificate-card">
    <div class="certificate-icon">
        <i class="fas fa-trophy"></i>
    </div>
    <h4>Nome do Certificado</h4>
    <button class="btn-certificate" onclick="openModal('nome-da-imagem.jpg')">
        Ver Certificado
    </button>
</div>
```

### Alterar Foto Pessoal
1. Substitua o arquivo `2025-07-20.png` pela nova foto
2. Ou altere o nome no `index.html`:
```html
<img src="nova-foto.jpg" alt="Magno Silva Andrade" class="profile-image">
```

## 📋 Checklist de Deploy

Antes de publicar o site, verifique:
- [ ] Todas as imagens estão carregando corretamente
- [ ] Links do WhatsApp funcionam
- [ ] Email e telefone direcionam corretamente
- [ ] Site é responsivo em diferentes tamanhos de tela
- [ ] Todos os certificados abrem no modal
- [ ] Navegação entre seções funciona
- [ ] Botão "voltar ao topo" aparece ao rolar

## 🌐 Como Publicar

### Opção 1: GitHub Pages
1. Crie um repositório no GitHub
2. Faça upload de todos os arquivos
3. Ative o GitHub Pages nas configurações
4. Seu site estará disponível em: `https://Kaio0369.github.io/curriculo`

### Opção 2: Netlify
1. Acesse netlify.com
2. Arraste a pasta do projeto para o Netlify
3. Seu site será publicado automaticamente

### Opção 3: Vercel
1. Acesse vercel.com
2. Conecte seu repositório GitHub
3. Deploy automático

## 📞 Suporte

Se precisar de ajuda ou tiver dúvidas sobre o código, você pode:
1. Verificar os comentários no código
2. Consultar a documentação das tecnologias usadas
3. Testar as funcionalidades localmente antes do deploy

## 🔧 Tecnologias Utilizadas

- **HTML5**: Estrutura semântica
- **CSS3**: Estilos modernos com Flexbox e Grid
- **JavaScript ES6+**: Funcionalidades interativas
- **Font Awesome**: Ícones profissionais
- **Google Fonts**: Tipografia (Inter)

---

**Desenvolvido para Magno Silva Andrade**  
Operador de Usina Sênior | Especialista em Sistemas Elétricos de Potência

