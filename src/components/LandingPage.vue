<template>
    <div class="container xxl">
        <div class="row">
                <div class="col-md-6 mt-5 ">
                    <iframe width="700" height="415" src="https://www.youtube.com/embed/tV3tXUW0xVE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>\
                    
                    <div class="row d-flex justify-content-between">
                        <div class="col-md-3">
                            <img src="../assets/es-og.jpg" alt="" id="img">
                            
                        </div>
                        <div class="col-md-3">
                            <img src="../assets/ones.jpg" alt="" id="img">
                            
                        </div>
                        <div class="col-md-3">
                            <img src="../assets/itachi.jpg" alt="" id="img">
                            
                        </div>
                    </div>    
                </div>
                <div class="col-md-6   text-center mt-5 ">
                    <h1 class="text-white">Dagohoy's Revolt</h1>

                    <div class="col-md-1 offset-2 mt-5">
                            <button type="button" class="btn btn-info btn-lg ">Download here for PC(exe)</button>
                            <button type="button" class="btn btn-info btn-lg">Download here for Androids(apk)</button>
                    </div>
                        <p class="text-white">Francisco Dagohoy led the longest revolt against the Spaniards in Philippine history.
                        The revolt took the Spaniards 85 years (1744-1829) to quell. Forced labor was one of the causes of the revolt.
                        But what triggered the decision to rise up in arms against the Spanish authorities in Bohol was the refusal of a 
                        Jesuit priest to give a Christian burial to Dagohoy's brother. Lorem ipsum dolor sit amet consectetur adipisicing elit. Aliquid esse praesentium, sequi quidem ratione, eligendi fugit, nemo natus est suscipit omnis consequuntur harum. Ex reprehenderit rerum quasi voluptate nisi iure! Lorem ipsum dolor sit amet consectetur adipisicing elit. Consequatur aliquid dolores maiores molestiae possimus? Ullam, cupiditate aliquam.
                        Harum corrupti, dignissimos ullam consequatur deleniti vero eaque pariatur hic id, fuga quaerat?
                        </p>
                </div>
        </div>   
    </div>
</template>
<script>
export default {
    data(){
        
    }
}
</script>
<style scoped>
    h1{
        margin-left: 3rem;
        margin-top: 5%;
        font-family: Castellar;
    }
    iframe{

        margin-top: 5%;
    }
        button{
        width: 29rem;
        margin-top: 10%;
        border-radius: 20px;
    }
        #img{
        background-size:cover ;
        height: 125px;
        width: 225px;
        border-radius: 2px;
        box-shadow: 0px 7px 14px #303436;
        cursor: pointer;
        transition: all 0.3s ease-out;
    }
        #img:hover{
        transform: scale(1.2);
        
    }
    p{  
        font-family: Leelawadee UI;
        margin-left: 10%;
        margin-top: 10%;
    }

</style>