# Criar o conteúdo do arquivo README.md
readme_content = """
# 💘 Desejo em Jogo – A Jornada da Paixão

**Desejo em Jogo** é uma experiência interativa de sedução para casais que desejam explorar fantasias, fortalecer a intimidade e transformar cada encontro em uma aventura provocante.

Este projeto é um webapp leve, sensual e responsivo, compatível com qualquer dispositivo — incluindo smartphones como Huawei — totalmente jogável direto no navegador, mesmo offline (com melhorias futuras).

---

## 🔥 Como Jogar

- Cada jogador tira uma carta por vez
- Escolha entre **FAZER o desafio** ou aceitar um **CASTIGO**
- Os castigos são sensuais, divertidos e estimulantes
- Tudo com base no **consentimento** e na excitação mútua

---

## 🎮 Funcionalidades

- Interface sensual e moderna
- Seleção de intensidade: **média, quente, muito quente**
- Modo escuro 🔥🌙
- Música de fundo envolvente
- Compatível com mobile (incluindo dispositivos sem Google)
- Totalmente em **HTML/CSS/JS puro**

---

## 📂 Como usar

1. Clone ou baixe este repositório
2. Abra o arquivo `index.html` no seu navegador
3. Aproveite o jogo com quem você ama ❤️‍🔥

> Também pode ser publicado via GitHub Pages, Netlify ou outro serviço gratuito de hospedagem estática.

---

## ✨ Autor

Criado com desejo por **Benet A. Alberto**

---

## 📸 Preview

![Desejo em Jogo – Preview](logo_desejo.png)

---

## 📜 Licença

Este projeto é licenciado para uso pessoal e íntimo 💋  
Não é permitido uso comercial sem autorização prévia.
"""

# Salvar o conteúdo em um arquivo README.md
file_path = "/mnt/data/README.md"
with open(file_path, "w", encoding="utf-8") as f:
    f.write(readme_content)

file_path
