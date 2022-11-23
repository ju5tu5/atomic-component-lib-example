<script>
  import Label from "../atoms/Label.svelte"
  import InputText from "../atoms/InputText.svelte"
  import Button from "../atoms/Button.svelte"
  import SearchImg from "../atoms/SearchImg.svelte"

  
</script>

<form action="/srch" method="get">
  <Label name="query">Zoeken</Label>
  <InputText name="query" />
  <Button type="submit">Zoek <SearchImg stroke="hotpink" /></Button>
</form>