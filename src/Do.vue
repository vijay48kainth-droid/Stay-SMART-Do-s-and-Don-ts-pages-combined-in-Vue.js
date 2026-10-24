<template>
    <div class="main-content-donts">
          <h2><u>Think SMART before you tap, type or click.</u></h2>
        <div id="dos-intro">

            <div class="do-side-header">
                <img
                    class="do-phone"
                    src="Do and Dont images/privecstasy-CXlqHmQy3MY-unsplash.jpg"
                >
            </div>

            <div id="dos-header-side">

                <div class="dos-title">
                    <h1>Do</h1>
                </div>
                <div class="dos-subheading">
                    {{DoSubheading}}

                </div>
                <p class="dos-paragraph">
                    {{DoParagraph}}
                </p>
            </div>
        </div>

        <p class="dos-paragraph">

        </p>
    
    </div>

</template>
<script>

export default {
    name:'Do',
    props: {
    DoSubheading: String,
    DoParagraph: String
}
}



</script>

<style>
.dos-paragraph{
    padding-bottom:20px;
    background-color: antiquewhite;
}
</style>