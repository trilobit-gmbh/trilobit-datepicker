# Datepicker

Stellt einen einfachen jQuery Datepicker für die weitere, individuelle Implementierung via Javascript zur Verfügung.

https://www.npmjs.com/package/@chenfengyuan/datepicker


**Einbindung**
```
<link  href="/assets/trilobit-datepicker/dist/datepicker.min.css" rel="stylesheet">
<script src="/assets/trilobit-datepicker/dist/datepicker.min.js"></script>
```
oder via `$GLOBALS`:
```
$GLOBALS['TL_CSS'][] = 'assets/trilobit-datepicker/dist/datepicker.min.css|static';
$GLOBALS['TL_JAVASCRIPT'][] = 'assets/trilobit-datepicker/dist/datepicker.min.js|static';
```

**Verwendung**
```
<input data-toggle="datepicker">
<textarea data-toggle="datepicker"></textarea>
<div data-toggle="datepicker"></div>
<script>
  $('[data-toggle="datepicker"]').datepicker();
</script>
```

**ergänzende Infos**
sind in der README.md unter `/assets/trilobit-datepicker/dist/README.md` zu finden.