<!-- svelte-ignore a11y-label-has-associated-control -->
<page actionBarHidden = "true" >
    <actionBar title='aa'/>
    <stackLayout class="statusBar">
        <!-- <label height="24" /> -->
        <label height="48" />
    <stackLayout />
    <stackLayout class="mainWin">
        <webView src="https://youtube.com" />
    </stackLayout>
</page>

<script lang="javascript">
    
    let message = "Blank Svelte Native App \n ? \n ㅇㅇ"
</script>

<style>
    .mainWin {
        transform: scale(0.95) rotate(2deg);
    }
    .statusBar {
        background-color: #3A53FF;
    }
    .info .fas {
        color: #3A53FF;
    }
    .info .fast {
        color: #3A53FF;
    }
    .info {
        font-size: 20;
    }
</style>
