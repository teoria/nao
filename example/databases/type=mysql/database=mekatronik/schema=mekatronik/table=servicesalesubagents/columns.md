# servicesalesubagents

**Dataset:** `mekatronik`

## Columns (17)

- Id (int32 NOT NULL)
- SupplierId (int32)
- Description (string(100))
- Date (timestamp(6) NOT NULL)
- Value (decimal(18, 2) NOT NULL)
- BankAccountId (int32)
- PaymentType_Id (int32 NOT NULL)
- PaymentTypeFee (decimal(18, 2) NOT NULL)
- EffectiveDate (timestamp(6))
- EffectiveValue (decimal(18, 2))
- InvoiceDate (timestamp(6))
- InvoiceNumber (string(200))
- PrevisionEmit (timestamp(6))
- Timestamp (timestamp(6) NOT NULL)
- CashFlowItem_Id (int32)
- Sale_Id (int32 NOT NULL)
- CompetenceDate (timestamp(6))
