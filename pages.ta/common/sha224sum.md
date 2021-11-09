# sha224sum

> SHA224 மறையீட்டு சரிகாண்தொகையைக் கணி.
> மேலும் விவரத்திற்கு: <https://www.gnu.org/software/coreutils/manual/html_node/sha2-utilities.html>.

- கோப்பின் SHA224 சரிகாண்தொகையைக் கணி:

`sha224sum {{கோப்பு}}`

- பலக் கோப்புகளின் SHA224 சரிகாண்தொகையைக் கணி:

`sha224sum {{கோப்பு1}} {{கோப்பு2}}`

- SHA224 சரிகாண்தொகைகளைக் கணித்து கோப்பில் எழுது:

`sha224sum {{கோப்பு1}} {{கோப்பு2}} > {{கோப்பு.sha224}}`

- SHA224 சரிகாண்தொகைகளுடைய கோப்பைப் படித்து கோப்புகளைச் சரிபார்:

`sha224sum --check {{கோப்பு.sha224}}`

- பிழையுற்ற கோப்புகளை மட்டும் காட்டு:

`sha224sum --check --quiet {{கோப்பு.sha224}}`