# Catálogo Black Friday 2026 — Luciane Lima Estética Avançada 👑

Catálogo mobile-first de alta conversão para apresentação dos protocolos da Black Friday (Novembro/2026) da Dra. Luciane Lima.

## ✨ Recursos Implementados

1. **Apresentação em Acordeões Interativos**:
   - Organizado e filtrável por objetivos (**Faciais** e **Corporais**).
   - Abertura e fechamento suaves, exibindo detalhes clínicos, para que é indicado e valores especiais.

2. **Box Padronizada para Fotos de Antes & Depois**:
   - Dimensão e proporção (`aspect-ratio: 4 / 3`) fixas em todos os tratamentos.
   - Enquanto a foto não é enviada, exibe um placeholder com visual escuro luxuoso.
   - Para adicionar a foto, basta salvar o arquivo na pasta `assets/` e definir o atributo `src` na tag `img` correspondente.

3. **Preços em Destaque**:
   - Destaque para o valor à vista e detalhamento das parcelas em até 12x.
   - Botão direto para agendamento via WhatsApp já com mensagem personalizada com o nome do procedimento e valor.

4. **Botão de Atendimento Flutuante com Vibração e Exit-Intent**:
   - Botão fixo *"Precisa de ajuda? Me chame"* com balão de suporte.
   - Vibração no celular (`navigator.vibrate`) e animação visual quando o cliente demonstra intenção de sair do site (cursor saindo do topo ou tempo de inatividade).
   - Modal suave de retenção convidando a tirar dúvidas antes de sair.

5. **Design Estético & Clean**:
   - Cores: Fundo preto profundo (`#06080d`), azul elétrico (`#38bdf8`) e azul escuro (`#1e40af`).
   - Tipografia limpa e fina (`Plus Jakarta Sans`), sem fontes cursivas.

---

## 📋 Protocolos Cadastrados

### Faciais
- **Botox (Toxina Botulínica)**: R$ 599,90 à vista ou 12x de R$ 58,90
- **Bioestimulador de Colágeno**: R$ 999,90 à vista ou 12x de R$ 99,90
- **Preenchimento com Ácido Hialurônico (o ml)**: R$ 749,90 à vista ou 12x de R$ 74,90
- **Tratamento Cicatriz de Acne c/ Radiofrequência Microagulhada (3 sessões)**: R$ 1.399,90 à vista ou 12x de R$ 139,90
- **Microagulhamento com Drug Delivery**: R$ 229,90 à vista
- **Limpeza de Pele com Dermaplaning**: R$ 180,00 à vista
- **Limpeza de Pele com Peeling**: R$ 159,90 à vista

### Corporais
- **Preenchimento Glúteo 20ml**: R$ 3.299,90 à vista ou 12x de R$ 329,90
- **Criolipólise (por região)**: R$ 249,90 à vista ou 12x de R$ 24,90

---

## 🖼️ Onde Adicionar as Fotos de Antes & Depois

No arquivo `index.html`, localize o ID de cada box e preencha o caminho da foto no `src`:

| Procedimento | ID no index.html | Sugestão de nome do arquivo |
| :--- | :--- | :--- |
| Botox | `#box-botox` | `assets/antes-depois-botox.jpg` |
| Bioestimulador | `#box-bioestimulador` | `assets/antes-depois-bioestimulador.jpg` |
| Preenchimento | `#box-preenchimento` | `assets/antes-depois-preenchimento.jpg` |
| Cicatriz de Acne | `#box-cicatriz-acne` | `assets/antes-depois-acne.jpg` |
| Microagulhamento | `#box-microagulhamento` | `assets/antes-depois-microagulhamento.jpg` |
| Dermaplaning | `#box-dermaplaning` | `assets/antes-depois-dermaplaning.jpg` |
| Peeling | `#box-peeling` | `assets/antes-depois-peeling.jpg` |
| Glúteo 20ml | `#box-gluteo` | `assets/antes-depois-gluteo.jpg` |
| Criolipólise | `#box-criolipolise` | `assets/antes-depois-criolipolise.jpg` |

---

## 📱 Visualização Local
```bash
npm start
# ou
node server.js
```
Acesse em: `http://localhost:3001` (ou `http://localhost:3000`).
