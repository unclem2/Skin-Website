<script>

</script>

<div class="SkinMain">
    <div style="border: 1px solid #202060"/>
    <div class="SkinDiv" style="margin-top: 15px; margin-bottom: 25px;">
        <button on:click={() => window.location.href='/skin/example'} class="SkinButton">
            <p class="SkinName">Example</p></button><br/><br/>
        <div style="border: 3px solid #202060"/>
    </div>
<!--------------------------------------------------------------------------------------------------------------------->
    <!--TODO Search-->
    <div style="text-align: center; margin-top: 15px" >
        <form id="Form" role="search" class="Form">
            <input type="search" id="query"
                   placeholder="skin..."
                   aria-label="Search through site content">
            <button class="SkinButtonSearch">Search</button>
        </form>
    </div>

<!--Todo Adding Skins here-->
    <div class="SkinDiv"><br/>

        <button on:click={() => window.location.href='/skin/Seoul_v10'} class="SkinButton">
            <p class="SkinName">Seoul_v10</p></button>

        <button on:click={() => window.location.href='/skin/azr8midnight_v1.4'} class="SkinButton">
            <p class="SkinName">azr8midnight_v1.4</p></button>

        <button on:click={() => window.location.href='/skin/letsGo'} class="SkinButton">
            <p class="SkinName">letsGo</p></button>

        <button on:click={() => window.location.href='/skin/-GN_unclem_ver'} class="SkinButton">
            <p class="SkinName">-GN_unclem_ver</p></button>

        <button on:click={() => window.location.href='/skin/Ekoro_Incandescent_Nebulae'} class="SkinButton">
            <p class="SkinName">Ekoro_Incandescent_Nebulae</p></button>
        
        <button on:click={() => window.location.href='/skin/WhiteCat_CK_(1.0)'} class="SkinButton">
            <p class="SkinName">WhiteCat_CK_(1.0)</p></button>
        
        <button on:click={() => window.location.href='/skin/BaconBoi'} class="SkinButton">
            <p class="SkinName">BaconBoi</p></button>
        
        <button on:click={() => window.location.href='/skin/Mrekk_2.0_(FY)'} class="SkinButton">
            <p class="SkinName">Mrekk_2.0_(FY)</p></button>

    </div>
<!--/Todo Adding Skins here-->

    <div class="SkinGoTopDiv SkinGoTop" on:click={() => window.scrollTo({ top: 0, behavior: 'smooth' })}>‹‹</div>
</div>

<style>

    .SkinMain {background-color: #202040; border-radius: 25px; margin-bottom: 165px; padding-bottom: 50px;}
    .SkinButtonSearch {
        width: 100px;
        background-color: #202060;
        border-style: solid;
        border-color: #2828a8;
        border-radius: 15px;
        color: #E3F4FF;
        font-size: 17px;
        cursor: pointer;
    }

    .SkinName {
        margin: 0px;
        font-size: 24px;
        word-wrap: break-word;
        color: #E3F4FF;
        text-decoration: none;
    }

    Form {
        background-color: #202060;
        width: 300px;
        height: 44px;
        display: flex;
        flex-direction: row;
        align-items: center;
        margin: auto;
        border-radius: 25px;
    }
    input {
        all: unset;
        font: 16px system-ui;
        color: #E3F4FF;
        height: 100%;
        width: 100%;
        padding: 0px 10px;
        text-align: center;
        margin: auto;
    }

    .SkinDiv {
        margin: auto;
        max-width: 2500px;
        text-align: center;
        color: #E3F4FF;
    }

    .SkinButton {
        margin: 5px;
        width: 75%;
        max-width: 400px;
        background-color: #202060;
        border-style: solid;
        border-color: #2828a8;
        border-radius: 15px;
        color: #E3F4FF;
        padding-top: 15px;
        padding-bottom: 15px;
    }
    .SkinButton:hover {
        background-color: #2828a8;
    }

    .SkinGoTopDiv {
        position: fixed;
        bottom: 115px;
        right: 0px;
        font-size: 50px;
        -webkit-user-select: none; /* Safari */
        -moz-user-select: none; /* Firefox */
        -ms-user-select: none; /* IE10+/Edge */
        user-select: none; /* Standard */
    }
    .SkinGoTop {
        text-decoration: none;
        color: #d9d9d9;
        display: inline-block;
        transform: rotate(90deg);
        margin-right: 15px;
        font-weight: bold;
    }

</style>
