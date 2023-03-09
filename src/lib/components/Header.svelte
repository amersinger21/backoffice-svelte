<script>
    import Logo from "$lib/assets/logo.svg";
    import MagnifyingGlass from "$lib/assets/magnifier.svg";
</script>

<header>
   <img src={Logo} alt="Brand Logo" class="w-8"> 
   <div class="search">
    <label for="search_input">Search by</label>
   <input id="search_input" class="search_input" name="search_input" type="text">
   <button class="search_button">
        <img src={MagnifyingGlass} alt="magnifying glass icon">
    </button>
   </div>
   
</header>

<style>
    img {
        width: 100%;
    }

    button {
        border: 1px solid rgba(110, 110, 110, 0.596);
        background: linear-gradient(#FFF, #cfcfcf);
        box-shadow: 0px 0px 2px rgb(54, 54, 54);
        width: 2rem;
        aspect-ratio: 1 / 1;
        display: flex;
        justify-content: center;
        align-items: center;
        padding: .25rem;
    }

    .search {
        display: flex;
        justify-content: center;
        align-items: center;
    }

    .search_input {
        margin-left: .5rem;
        min-height: 2rem;
    }
</style>
 