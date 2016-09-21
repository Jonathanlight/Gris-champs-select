# Gris-champs-select


<style>

#grey{color:#aaa;}
#black{color:#000;}
select{
  text-align: center;
  padding: 10px;
}
</style>

<select>
  <option id = "grey">Selectionné Ici</option>
  <option id = "black">option 1</option>
  <option id = "black">option 2</option>
  <option id = "black">option 3</option>
  <option id = "black">option 4</option>
  <option id = "black">option 5</option>
</select>

<script>
$("select").change(function(){
    $(this).css("color", $(this).children("option:selected").css("color")); 
});

$("select").css("color", "grey");

</script>




