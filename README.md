<h1 align="center">🌍 GlobalConnect Unifor</h1>

<p align="center">
  <b>O intercâmbio da Unifor em um só lugar: do edital ao acompanhamento da candidatura.</b><br>
  Projeto de Requisitos e Modelagem de Sistemas · Equipe 2 · Internacionalização
</p>

<p align="center">
  <a href="https://claude.ai/artifact/LTj5QFfjPhncpHS4FNrqVY"><b>📱 Abrir o protótipo navegável</b></a>
</p>

---

## 📌 O problema

> *"Eu nunca sabia em que fase meu processo estava."* — Luan, ex-intercambista (Educação Física, Unifor)

Quem quer fazer intercâmbio na Unifor não tem um lugar único para achar oportunidades, entender os requisitos, enviar documentos e acompanhar a candidatura. Hoje isso passa por redes sociais, PDF do site, e-mail, WhatsApp e idas ao setor.

| Quem sente | Principal dor |
|---|---|
| **Interessados** | Não sabem por onde começar nem se podem participar |
| **Candidatos** | Documentos dispersos e nenhuma visibilidade do andamento |
| **Gestão e coordenação** | Recebem documentos incompletos e avisos atrasados |

## 🔎 Como investigamos

| 4 entrevistas | 30 respostas analisadas | 12 dores identificadas |
|:-:|:-:|:-:|

Entrevistamos um ex-intercambista, dois estudantes interessados e um ex-coordenador de curso (visão externa, UFC). Principais descobertas:

- **3 de 3** estudantes buscam informação em redes sociais, colegas e links de terceiros → *fonte oficial única*
- **3 de 3** têm dificuldade de ler e navegar pelo celular → *solução pensada primeiro para o celular*
- **3 de 3** citam o dinheiro como preocupação → *custos estimados por oportunidade*
- **1 relato** de vergonha de perguntar algo "óbvio" → *FAQ público, sem precisar de login*

## 💡 A solução

Um portal web, adaptável ao celular, que reúne **oportunidades, editais, documentos e acompanhamento da candidatura**.

| Funcionalidade | Dores atendidas |
|---|---|
| Informação oficial em um lugar: oportunidades, editais e FAQ | D04 · D07 · D08 |
| Documentos em uma lista única: checklist e envio com comprovante | D01 · D10 |
| Acompanhamento claro: etapa, pendência e próxima ação | D02 |
| Painel para a gestão: candidaturas, análise e pendências | D11 |

### O percurso em cinco telas

1. **Explorar** — busca, filtros e favoritos
2. **Oportunidade** — prazo, requisitos e custos
3. **Documentos** — lista única e situação de cada um
4. **Minha jornada** — etapas e próxima ação
5. **Painel da gestão** — casos e pendências

O protótipo 2.0 também traz versão em **português e inglês**, **tema claro e escuro**, comparação de destinos lado a lado, calculadora de custos, guias de preparação, atendimento com a DRI/NEI e uma área para estudantes estrangeiros.

## 🧩 Rastreabilidade: da entrevista à tela

```
Fala (Luan) → Dor D02 → Requisito RF14 → História US16 (Must) → Tela "Minha jornada"
```

| 30 respostas | 12 dores | 28 RF + 11 RNF | 32 histórias | 12 histórias Must | 23 telas |
|:-:|:-:|:-:|:-:|:-:|:-:|

**Modelagem:** diagrama de casos de uso com 3 atores (visitante, estudante e gestor), 2 diagramas de atividades (submissão e análise de documentos) e **76 critérios de aceitação** no formato *Dado, Quando, Então*.

## ✅ Validação com usuários

Três estudantes usaram a primeira versão do protótipo:

- **2 de 3** pediram melhor acompanhamento da candidatura
- **2 de 3** pediram informação mais clara e oficial
- **8 ajustes** aplicados: avisos de andamento, etapas concluídas e pendentes, requisitos e custos no edital, contato da DRI/NEI sempre visível

> Ainda não medido: tempo e sucesso por tarefa (meta RNF03: 4 de 5 estudantes em até 5 minutos). A versão 2.0 ainda não foi testada com usuários.

## 🚀 O MVP: 12 histórias *Must*

| Acesso e descoberta | Editais e parceiros | Candidatura | Acompanhamento e gestão |
|---|---|---|---|
| US01 Acessar a área privada | US03 Publicar editais | US11 Preparar checklist | US16 Consultar andamento |
| US04 Encontrar oportunidades | US02 Manter parceiros e convênios | US12 Enviar documento | US15 Analisar documentos |
| US09 Consultar FAQ público | | US14 Submeter candidatura | US18 Consultar painel |
| | | US13 Corrigir documento | |

**9 de 12 dores** têm ao menos uma função no MVP.

| Situação | Conteúdo |
|---|---|
| **Prototipado** | App navegável (v2.0), estudante e gestão ligados, dados de exemplo |
| **Validado** | Rodada qualitativa na v1 com 3 usuários e 8 ajustes |
| **Proposto como MVP** | 12 histórias Must, ainda não desenvolvidas |
| **Futuro** | 10 *Should* (despesas, notificações, plano de estudos) · 3 *Could* (relatórios, relatos, eventos) |

> ⚠️ Protótipo navegável com **dados de exemplo**: não há um sistema real por trás. Regras ainda a validar com a DRI/NEI.

## 👥 Equipe 2

- Caueh Bento de Lima Mota
- David Gonçalves da Silva
- Matheus Lucas Oliveira
- João Cláudio Gonçalves Linhares
- Miguel Asafe Silva de Almeida
- Jorge Gabriel Pinheiro Frutuoso

**Professor:** Gerhard Saboia · **Disciplina:** Requisitos e Modelagem de Sistemas (T193-90) · **UNIFOR** · Novembro de 2026
