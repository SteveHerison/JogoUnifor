# 🎮 Jogos de Biodinâmica do Corpo Humano

Site educacional interativo com 3 jogos para aprendizado de anatomia e biomecânica.

## 📚 Conteúdo do Projeto

### Jogo 1: Quebra-Cabeça das Alavancas
Identifique os tipos de alavancas no corpo humano através de 3 níveis de dificuldade:
- **Nível Fácil**: 3 questões sobre conceitos básicos
- **Nível Médio**: 4 questões com aplicações práticas
- **Nível Difícil**: 5 questões de raciocínio biomecânico

**Como jogar:**
1. Leia a pergunta sobre um movimento corporal
2. Digite a resposta (1ª classe, 2ª classe ou 3ª classe)
3. Receba feedback instantâneo e pontuação

### Jogo 2: Quem Sou Eu?
Adivinhe 7 articulações principais através de dicas progressivas:
- Ombro, Cotovelo, Punho/Mão, Coluna Vertebral, Quadril, Joelho, Tornozelo/Pé

**Como jogar:**
1. Leia as dicas reveladas
2. Clique para revelar mais dicas (quanto menos dicas usar, mais pontos ganha!)
3. Digite o nome da articulação
4. Sistema de pontuação: 20 pontos - (2 pontos por dica extra)

### Jogo 3: Movimento em Ação
Identifique músculos e movimentos através de 5 questões de múltipla escolha com imagens ilustrativas:
- Agachamento
- Flexão de cotovelo
- Elevação dos calcanhares
- Corrida (fase de impulso)
- Abdução de ombro

**Como jogar:**
1. Observe a imagem do movimento
2. Leia a pergunta
3. Clique na resposta correta
4. Receba feedback imediato com a resposta correta destacada

## 🚀 Como Executar

### Opção 1: Abrir diretamente no navegador
1. Localize o arquivo `index.html` na pasta do projeto
2. Clique duas vezes para abrir no navegador
3. Comece a jogar!

### Opção 2: Usando um servidor local (recomendado)

#### Com Python:
```bash
# Python 3
python -m http.server 8000

# Acesse: http://localhost:8000
```

#### Com Node.js (http-server):
```bash
npx http-server -p 8000

# Acesse: http://localhost:8000
```

#### Com PHP:
```bash
php -S localhost:8000

# Acesse: http://localhost:8000
```

## 📂 Estrutura do Projeto

```
ProjetoJogo/
├── index.html              # Página principal
├── css/
│   └── style.css          # Estilos completos
├── js/
│   ├── data.js            # Dados dos jogos (perguntas, respostas)
│   └── main.js            # Lógica dos jogos
├── images/                # Imagens dos exercícios
│   ├── WhatsApp Image 2025-11-03 at 10.44.19 AM.jpeg       (Agachamento)
│   ├── WhatsApp Image 2025-11-03 at 10.44.19 AM (1).jpeg   (Abdução ombro)
│   ├── WhatsApp Image 2025-11-03 at 10.44.19 AM (2).jpeg   (Músculo braço)
│   ├── WhatsApp Image 2025-11-03 at 10.44.19 AM (3).jpeg   (Flexão cotovelo)
│   ├── WhatsApp Image 2025-11-03 at 10.44.20 AM.jpeg       (Elevação calcanhar)
│   └── WhatsApp Image 2025-11-03 at 10.44.20 AM (1).jpeg   (Corrida)
└── README.md              # Este arquivo
```

## 🎨 Recursos

- ✅ Design responsivo (funciona em desktop, tablet e mobile)
- ✅ Animações suaves e feedback visual
- ✅ Sistema de pontuação por jogo
- ✅ Navegação intuitiva entre jogos e níveis
- ✅ Tela de resultados com análise de desempenho
- ✅ Tecla Enter para enviar respostas
- ✅ Interface colorida e amigável

## 🎯 Funcionalidades

### Sistema de Pontuação
- **Jogo 1**: 10 pontos por acerto
- **Jogo 2**: 10-20 pontos (baseado em quantas dicas foram usadas)
- **Jogo 3**: 10 pontos por acerto

### Feedback Visual
- ✅ Verde para respostas corretas
- ❌ Vermelho para respostas incorretas
- 💡 Explicações detalhadas após cada resposta

### Tela de Resultados
- 🏆 100% = Perfeito!
- 🎉 70-99% = Muito bem!
- 👍 50-69% = Bom trabalho!
- 📚 0-49% = Continue praticando!

## 🛠️ Tecnologias Utilizadas

- **HTML5**: Estrutura semântica
- **CSS3**: Animações, gradientes, responsividade
- **JavaScript (Vanilla)**: Lógica dos jogos, navegação, pontuação

## 📱 Compatibilidade

- ✅ Chrome, Firefox, Safari, Edge (versões modernas)
- ✅ Dispositivos móveis (iOS e Android)
- ✅ Tablets
- ✅ Desktops

## 🎓 Conteúdo Educacional

Baseado em conceitos de:
- Biomecânica do movimento humano
- Anatomia musculoesquelética
- Tipos de alavancas corporais
- Articulações e movimentos
- Ações musculares

## 🔧 Personalização

### Adicionar novas perguntas:
Edite o arquivo `js/data.js` e adicione novos objetos aos arrays:
- `alavancasData` (para o jogo de alavancas)
- `quemSouEuData` (para o jogo Quem Sou Eu)
- `movimentoAcaoData` (para o jogo de movimentos)

### Modificar cores:
Edite as variáveis CSS no arquivo `css/style.css`:
```css
:root {
    --primary-color: #4F46E5;
    --secondary-color: #7C3AED;
    --success-color: #10B981;
    /* ... */
}
```

## 📝 Notas

- As imagens devem estar na pasta `images/`
- Para melhor performance, use um servidor local
- Testado em navegadores modernos
- Não requer conexão com internet após carregar

## 🤝 Créditos

Desenvolvido para estudos de Biodinâmica do Corpo Humano.
Conteúdo baseado em material educacional de anatomia e biomecânica.

---

**Divirta-se aprendendo!** 🎉
# JogoUnifor
