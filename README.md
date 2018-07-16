# selecto
selectbox replacement

```
<link rel="stylesheet" href="selecto.css">
```

just add class="selecto" in selectbox tag and replace *selected* with *data-selected="true"* for selected option. if you not defined the option value, selecto will define the value same as option text.

```
<select class="selecto" placeholder="">
  <option data-selected="true">Jakarta</option>
  <option>Surabaya</option>
  <option>Medan</option>
  <option>Bandung</option>
  <option>Makassar</option>
  <option>Semarang</option>
  <option>Palembang</option>
</select>
```

for multiple selectbox, just add multiple in selectbox.

```
<select class="selecto" placeholder="" multiple>
  <option data-selected="true">Jakarta</option>
  <option>Surabaya</option>
  <option data-selected="true">Medan</option>
  <option>Bandung</option>
  <option>Makassar</option>
  <option>Semarang</option>
  <option>Palembang</option>
</select>
```

```
<script src="selecto.min.js"></script>
```
