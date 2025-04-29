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
  TIMENOW() >= TIME("00:01:00"),
  TIMENOW() <= TIME("23:59:00")
)
)
