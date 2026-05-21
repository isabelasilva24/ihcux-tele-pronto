# TelePronto — Protótipo de Baixa Fidelidade

Projeto desenvolvido para a disciplina de Interação Humano Computador e UX (IHC & UX) do Centro Universitário UNA.

## 📚 Disciplina
**Interação Humano Computador e UX**  
Professor: Daniel Henrique Matos de Paiva

---

# 👨‍💻 Integrantes

- Isabela Silva
- Lucas Silva
- Lucas Paulino
- Olavo
- Matheus

---

# 🏥 Sobre o Projeto

O **TelePronto** é um aplicativo de telemedicina criado para reduzir a sobrecarga do pronto-socorro físico, permitindo que pacientes realizem triagem digital, consultas online e gerenciamento de receitas médicas diretamente pelo celular.

O protótipo foi desenvolvido utilizando wireframes de baixa fidelidade no Miro, priorizando:

- Simplicidade visual
- Facilidade de navegação
- Acessibilidade
- Clareza das informações
- Rapidez no atendimento

---

# 📱 Funcionalidades do Protótipo

O aplicativo possui as seguintes funcionalidades principais:

## 1. Home / Dashboard
Tela inicial com acesso rápido para:
- Consulta imediata
- Meus remédios
- Histórico médico
- Farmácias próximas

---

## 2. Fluxo de Triagem
O usuário informa:
- Região da dor
- Sintomas
- Intensidade
- Tempo dos sintomas

A interface utiliza:
- Botões grandes
- Pouco texto por tela
- Linguagem simples

---

## 3. Sala de Espera Virtual
Exibe:
- Quantidade de pacientes na fila
- Tempo estimado de espera
- Status do médico
- Avisos importantes

---

## 4. Interface de Videochamada
Permite:
- Conversa por vídeo com o médico
- Ativar/desativar câmera
- Ativar/desativar microfone
- Chat de apoio

---

## 5. Minha Receita
Exibe:
- Receita digital
- QR Code
- Nome do medicamento
- Dosagem
- Data da prescrição

---

## 6. Configuração de Alarmes
Permite configurar:
- Horário do medicamento
- Frequência
- Nome do remédio
- Notificações automáticas

---

# 🔄 Fluxo Crítico

O fluxo principal para uma consulta de urgência ocorre da seguinte forma:

1. Usuário acessa a Home
2. Seleciona “Consulta Agora”
3. Realiza a triagem rápida
4. Sistema classifica o atendimento
5. Usuário entra na fila virtual
6. Médico inicia a videochamada
7. Receita digital é disponibilizada ao final

O fluxo foi projetado para exigir o menor número possível de etapas.

---

# ♿ Análise de Acessibilidade

O design foi pensado especialmente para usuários idosos ou em situação de mal-estar.

## Medidas adotadas:

### ✅ Texto legível
- Fontes grandes
- Alto contraste
- Pouca informação por tela

### ✅ Botões acessíveis
- Áreas de clique grandes
- Espaçamento adequado
- Ícones simples

### ✅ Navegação simplificada
- Fluxo linear
- Poucas decisões por etapa
- Botões principais destacados

### ✅ Redução de esforço cognitivo
- Linguagem objetiva
- Uso mínimo de elementos visuais
- Hierarquia clara das informações

### ✅ Situações de visão turva ou mãos trêmulas
O sistema evita:
- Botões pequenos
- Menus complexos
- Excesso de texto
- Ações próximas que possam gerar toques acidentais

---

# 🛡️ Prevenção de Erros

Para evitar problemas durante a consulta:

## Medidas implementadas:

- Confirmação antes de encerrar a chamada
- Botão “Sair” afastado dos controles principais
- Avisos visuais durante a consulta
- Estado da conexão sempre visível
- Mensagens claras de erro

Exemplo:
> “Deseja realmente encerrar a consulta?”

---

# 🚨 Botão de Emergência

O botão de emergência permanece visível em todas as telas do aplicativo.

Objetivo:
- Permitir acesso rápido ao suporte
- Direcionar casos graves imediatamente ao pronto atendimento físico

---

# 📶 Estados do Sistema

O protótipo apresenta feedback constante para o usuário:

## Exemplos:
- “Aguardando médico entrar na chamada”
- “Conexão instável”
- “Triagem enviada com sucesso”
- “Receita disponível”

Isso reduz ansiedade e aumenta a sensação de segurança.

---

# 👨‍👩‍👧 Desafio Extra — Dependentes

O sistema permite alternar entre perfis:

- Adulto
- Filho(a)
- Dependente idoso

Facilitando:
- Consultas pediátricas
- Controle de medicamentos
- Histórico individual

---

# 🌐 Desafio Extra — Baixa Conexão

Em conexões instáveis:

- O vídeo é automaticamente reduzido
- O sistema prioriza o áudio
- Uma mensagem informa o usuário

Exemplo:
> “Sua internet está instável. O vídeo foi reduzido para melhorar o áudio.”

---

# 🛠 Ferramentas Utilizadas

- Miro
- GitHub

---

# 📂 Estrutura do Repositório

```bash
ihcux-tele-pronto/
│
├── prototipo/
│   ├── prototipo.png
│   └── prototipo.pdf
│
└── README.md
