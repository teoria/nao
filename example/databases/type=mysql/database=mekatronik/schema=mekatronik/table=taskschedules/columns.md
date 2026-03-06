# taskschedules

**Dataset:** `mekatronik`

## Columns (16)

- Id (int32 NOT NULL)
- CreatorId (int32 NOT NULL)
- AssignedId (int32)
- BoardId (int32 NOT NULL)
- OccurrenceTotal (int32 NOT NULL)
- OccurrenceCount (int32 NOT NULL)
- Deadline (int32 NOT NULL)
- StopCriteria (int32 NOT NULL)
- Occurrence (int32 NOT NULL)
- StartDate (timestamp(6) NOT NULL)
- EndDate (timestamp(6))
- Timestamp (timestamp(6) NOT NULL)
- NextSchedule (timestamp(6) NOT NULL)
- Active (int8 NOT NULL)
- WeekDays (string(100))
- TaskId (int32 NOT NULL)
