# 💡 Ailumination

**Ailumination** é um agente de IA multimodal projetado para atuar como um motor de pós-produção e iluminação atmosférica em ilustrações e desenhos artísticos. 

O principal objetivo deste projeto é resolver um desafio comum em ferramentas generativas de IA: aplicar um jogo de luz dramático e realista **sem alterar ou re-renderizar a pintura, os traços e a identidade visual original da obra**.

---

## 🚀 Como Funciona (Pipeline de Execução)

O agente opera seguindo estritamente um pipeline de 3 fases estruturado via *System Instructions*:

1. **Análise e Bloqueio Global:** O agente mapeia a paleta de cores predominante da ilustração e aplica um isolamento rígido, blindando 100% os traços, linhas, contornos e preenchimentos originais.
2. **Definição de Preferências:** Processa comandos de direção de luz, paleta de cores e intensidade fornecidos pelo usuário. Caso não sejam especificados, o agente realiza uma *Harmonia Cromática Inteligente*, extraindo automaticamente os tons da própria obra para guiar a iluminação.
3. **Renderização da Camada de Luz:** Aplica feixes volumétricos (*Light Shafts*), brilho de contorno (*Rim Lighting*) e sombras de forma exclusiva no plano de fundo e espaço negativo, proibindo estritamente a criação de novos elementos na cena.

---

## 🎨 Exemplo de Uso

O agente aceita ilustrações e aplica a atmosfera baseada nas preferências ou nas cores nativas:

| Desenho Cru (Entrada) | Desenho Iluminado (Saída com Ailumination) |
| :--------------------: | :-----------------------------------------: |
| <img src="https://github.com/user-attachments/assets/e07ea9a1-3f0d-4ad3-accf-bb8ef0b3d112" width="300" alt="Desenho Cru"> | <img src="https://github.com/user-attachments/assets/8b951522-d360-4ec1-8ab0-d15a29c0dbd8" width="300" alt="Desenho Iluminado"> |

---

## 🛠️ Como Utilizar o Agente

1. Acesse o **Google AI Studio**.
2. Crie um novo chat/prompt (*Chat prompt*).
3. No painel lateral direito de configurações, selecione o modelo **Nano Banana 2 Lite** (`gemini-3.1-flash-lite-image`) para garantir a fidelidade de imagem e edição adequadas.
4. Copie o prompt estruturado disponível na pasta `/prompts` deste repositório e cole nas **System instructions**.
5. Envie sua ilustração junto com suas preferências de luz (opcional)!

---

## 👩‍💻 Autora
Desenvolvido por **Ana Júlia Alemar de Souza** — [GitHub](https://github.com/anajuliaalemar) | [LinkedIn](https://www.linkedin.com/in/anajuliaalemar)
