# Parte 4 — Sistema de Tipos Ontológicos

Para que qualquer discussão seja produtiva, cada termo utilizado deve passar por uma "checagem de tipos". Se tentarmos realizar operações lógicas entre tipos incompatíveis (ex: tratar uma ficção da C5 como um fato da C1), o sistema entrará em colapso em uma falácia.

## 4.1 Taxonomia de Referentes
Classificamos cada termo de acordo com a natureza daquilo que ele aponta dentro das camadas (C0-C5):

| Tipo | Rótulo | Descrição Operacional | Exemplo |
| :--- | :--- | :--- | :--- |
| **RAW** | `v0` | O objeto na C0, antes de ser medido ou nomeado. A "coisa em si". | O espectro antes de Newton. |
| **ACCESSIBLE** | `v1` | Fenômenos da C1/C2 verificados pelo Pipeline. Possuem poder preditivo. | Gravidade, oxigênio, voltagem. |
| **CONVENTION** | `v2` | Construções da C4/C5 com autores ou consenso social. São "corretas", mas não "verdadeiras". | Dinheiro, linguagem, PIB. |
| **INDEFINITE** | `v?` | Conceitos em processo de validação ou sem dados suficientes da C1. | Buracos de minhoca, consciência. |
| **DANGLING** | `v-err` | Ponteiros soltos. Palavras que não possuem referente em nenhuma camada ou são puramente circulares. | Destino, sorte, "o sistema" (como entidade). |

## 4.2 Regra de Instância vs. Classe
Um erro comum é confundir uma **classe** (um rótulo da C4) com uma **instância** (um objeto na C1).
* **Instância (C1):** O cão específico que te mordeu (um objeto físico com massa e comportamento).
* **Classe (C4):** "Periculosidade canina" (uma abstração social).
Operar sobre a classe como se fosse uma instância é uma falha de tipo que resulta em políticas públicas ineficientes e debates circulares.

## 4.3 O Algoritmo de Rotulagem
Antes de processar um argumento, cada substantivo deve ser submetido ao seguinte teste:

1.  **Possui massa, energia ou informação mensurável?** -> Marcar como `v1`.
2.  **Desapareceria se todos os humanos parassem de acreditar nele?** -> Marcar como `v2`.
3.  **A definição depende exclusivamente de outras palavras sem tocar na C1?** -> Marcar como `v-err`.

## 4.4 Erro de Tipo (Type Mismatch)
A maioria dos conflitos sociais ocorre devido a um erro de tipo não detectado.
* **Erro de Tipo A:** Tratar um `v2` (Ficção Social) como um `v1` (Realidade Física). *Exemplo: "A economia deve crescer por lei natural".*
* **Erro de Tipo B:** Tentar modificar um `v1` (Realidade Física) usando ferramentas de `v2` (Retórica). *Exemplo: "Decretamos que a gravidade é opressiva".*

## 4.5 O Status "Dangling"
Um termo `v-err` é radioativo para o conhecimento. Se uma conversa incluir mais de 20% de ponteiros soltos, o framework recomenda abortar a comunicação. Nesses casos, a informação não está sendo trocada; em vez disso, os participantes estão apenas sincronizando estados emocionais (C3) sem uma âncora.

---
*Este sistema de tipos torna o framework auditável: se um termo muda de tipo, deve haver um commit justificando a nova evidência na C1.*