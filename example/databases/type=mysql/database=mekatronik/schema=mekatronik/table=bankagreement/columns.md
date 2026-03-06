# bankagreement

**Dataset:** `mekatronik`

## Columns (20)

- Id (int32 NOT NULL)
- Wallet (string(6))
- Agreement (string(100))
- AdditionalInfo (string(100))
- Status (int32 NOT NULL)
- RegisterNumber (int32 NOT NULL)
- OurNumber (int32 NOT NULL)
- DocumentNumber (int32 NOT NULL)
- LateFeeType (int32 NOT NULL)
- LateFee (decimal(18, 2) NOT NULL)
- InterestType (int32 NOT NULL)
- Interest (decimal(18, 2) NOT NULL)
- ProtestDayType (int32 NOT NULL)
- ProtestDays (int32 NOT NULL)
- ReturnDayType (int32 NOT NULL)
- ReturnDays (int32 NOT NULL)
- Assignor_Id (int32)
- BankAccount_Id (int32)
- Name (string(100) NOT NULL)
- Timestamp (timestamp(6) NOT NULL)
