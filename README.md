# IDENTIF v9.5 — preservação total

Esta versão corrige a regressão da 9.4.

## Mantido/restaurado
- Registro com veículo e sem veículo.
- Data/hora REAL da ocorrência, separada da data/hora do registro.
- Fotos e vídeos.
- Várias mídias por ocorrência.
- 📎 ADICIONAR FOTO/VÍDEO vinculado à ocorrência existente.
- 🔎 COMPARAR OCORRÊNCIAS por placa.
- 📊 ANÁLISE DOS EVENTOS.
- 📞 LIGAÇÕES SUSPEITAS.
- Número informado ou registro sem número.
- Tipo de ligação e vários prints.
- Backup e restauração.
- PWA/atalho para celular.

## Preservação de dados
A versão usa armazenamento separado para não sobrescrever os dados anteriores e tenta migrar automaticamente várias chaves legadas conhecidas. Também inclui backup JSON completo, com as mídias quando elas estão acessíveis.

IMPORTANTE: uma página nova não consegue adivinhar uma mídia que o navegador anterior armazenou apenas em um banco privado incompatível. Por isso, o backup da versão anterior deve ser usado quando disponível. A versão 9.5 não apaga os dados antigos.

## Ajuste desta edição
- Mantida a base da v9.5.
- Uma ocorrência com veículo pode ser salva sem informar a placa.
- A placa continua opcional: se informada, é armazenada normalmente.
- Não foi alterado o funcionamento de câmera, microfone, fotos, vídeos, mídias ou armazenamento.

## Teste recomendado
1. Extraia o ZIP.
2. Abra index.html.
3. Confira se as ocorrências antigas aparecem.
4. Abra uma ocorrência e use 📎 ADICIONAR FOTO/VÍDEO.
5. Confirme que o contador aumentou e que as mídias anteriores continuam.
6. Teste LIGAÇÕES SUSPEITAS.


## Correção de mídia no histórico
- As fotos das ocorrências agora podem ser abertas ao tocar na miniatura.
- Os vídeos aparecem como miniaturas clicáveis e abrem em um visualizador com reprodução e controles.
- É possível navegar por todas as mídias da ocorrência (anterior/próxima).
- A área Últimas ocorrências mantém as mídias e permite abrir/reproduzir sem alterar o cadastro.
- Nenhuma outra regra da v9.5 foi removida: placa continua opcional, ocorrência sem veículo, data real, anexos, backup e demais módulos permanecem.
