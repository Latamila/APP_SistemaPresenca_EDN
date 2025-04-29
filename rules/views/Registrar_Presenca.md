AND(
  ISBLANK(
    FILTER(
      "presenca",
      AND(
        [Email] = USEREMAIL(),
        [Data] = TODAY()
      )
    )
  ),
  AND(
  TIMENOW() >= TIME("19:00:00"),
  TIMENOW() <= TIME("19:30:00")
)
)
