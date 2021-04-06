
## Using obsolete form feature
Contributed by: jlnprssnr

```{ABAP
FORM is_even USING input output.
  IF ( input MOD 2 = 0 ).
    output = abap_true.
  ELSE.
    output = abap_false.
  ENDIF.
ENDFORM.

```
