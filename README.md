# T20 Hayd — Itens Superiores e Mágicos

Automação de **melhorias, encantos e materiais especiais** de itens do **Tormenta20** (Livro Básico, Ameaças, Heróis e Deuses de Arton) no **FoundryVTT v13**. Substitui a aba de aprimoramentos nativa do sistema por uma versão sem limite de slots e com preço automático.

## O que faz

- Adiciona a aba **"Melhorias & Encantos"** às fichas de item (armas, armaduras, itens, etc.).
- **Sem limite de slots**: aplique quantas melhorias e encantos quiser no mesmo item.
- **Ajuste automático de preço** do item conforme as melhorias/encantos/materiais aplicados.
- **Materiais especiais** destacados visualmente.
- Automação da **Injeção Alquímica**.
- Suporte a **homebrews** (melhorias e encantos personalizados).
- **Editor de Efeitos** (Mestre): personalize os efeitos de qualquer melhoria/encanto do catálogo.

## Como usar

1. Ative o módulo no mundo.
2. Abra a ficha de um item físico (arma, armadura, equipamento…).
3. Vá até a aba **Melhorias & Encantos** e adicione os aprimoramentos desejados — o preço do item é recalculado automaticamente.

## Ferramentas do Mestre

Em *Configurar → Configurações → T20 Hayd — Itens*:

- **Editor de Efeitos** — abre um gerenciador (com busca e filtro) de todas as melhorias, encantos e materiais do catálogo. Cada entrada tem um editor no estilo do sistema: tipo do efeito, custo em PM, se é situacional/por cena, condições e a tabela de mudanças (chave/modo/valor) com autocompletar. As alterações são salvas como *overrides* no mundo (sobrepõem o catálogo padrão), com botão de **restaurar padrão** por entrada.
- **Gerenciar Homebrews** — crie melhorias, encantos e materiais especiais personalizados, disponíveis em todos os itens.
- Um interruptor permite **desabilitar a automação exclusiva da Injeção Alquímica**, caso prefira aplicá-la à mão.

## Requisitos

- FoundryVTT **v13**
- Sistema **Tormenta20** (mínimo **1.5.0**)

## Instalação

Em *Configurar → Módulos Complementares → Instalar Módulo*, cole a URL do manifesto:

```
https://raw.githubusercontent.com/Haydgi/t20-hayd-itens/main/module.json
```

## Aviso

Módulo não oficial, sem afiliação com a Jambô Editora ou com os autores de Tormenta20.
