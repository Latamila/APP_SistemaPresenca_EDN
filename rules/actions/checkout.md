AND(ISBLANK([HoraCheckout]),
  TIMENOW() >= TIME("20:45:00"),
  TIMENOW() <= TIME("21:00:00")
)

