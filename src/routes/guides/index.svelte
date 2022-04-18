<script context="module">
// this script area is in adition of the next one script area 
// this script run on the server to fetch the data so it can pre-render templates 
// expose the API to use it ... 
  export async function load() {

  }
</script>
<script>

</script>

<div class="guides">
  <ul>
    <li><a href="/">Guide 1</a></li>
    <li><a href="/">Guide 2</a></li>
  </ul>
</div>

<style>
  .guides {
    margin-top: 20px;
  }
  ul {
    list-style-type: none;
    padding: 0;
  }
  a {
    display: inline-block;
    margin-top: 10px;
    padding: 10px;
    border: 1px dotted rgba(255,255,255,0.2)
  }
</style>