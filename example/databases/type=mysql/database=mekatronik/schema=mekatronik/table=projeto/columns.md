# projeto

**Dataset:** `mekatronik`

## Columns (19)

- Id (int32 NOT NULL)
- Nome (string(100) NOT NULL)
- Description (string(2000))
- Cor (string)
- Ativo (int8 NOT NULL)
- PodeReportar (int8 NOT NULL)
- ComentarioObrigatorio (int8 NOT NULL)
- HoursWithBeginningEnd (int8 NOT NULL)
- BlockFutureReport (int8 NOT NULL)
- ReportOnDate (int8 NOT NULL)
- IsPrivate (int8 NOT NULL)
- Rateio (int32 NOT NULL)
- DataInicial (timestamp(6))
- DataFinal (timestamp(6))
- CustoPlanejado (float64 NOT NULL)
- ParentId (int32)
- Categoria_Id (int32)
- StatusTemplateId (int32)
- RealEndDate (timestamp(6))
