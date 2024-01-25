
Clickthrough Rate MOM Icon =
VAR IconPositive = UNICHAR(9650)
VAR IconeNegative = UNICHAR (9660)
VAR Result =
IF(
[ClickThroughRate]> [Clickthrough Rate PM],
IconPositive,
IconeNegative
)
RETURN
Result
