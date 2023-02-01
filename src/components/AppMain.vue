<script>
export default {
    name: 'AppMain',
    data(){
        return{

        }
    }
}
</script>
<template>
<main>
    <section class="jambotron">
    </section>
    <section  id="introduction">
        <div class="container text-center p-5">

            <div class="row d-flex">
                <div class="col">
                    <h4>WHO WE ARE</h4>
                    <P>Lorem ipsum,Fuga accusantium rerum ducimus harum autem saepe repudiandae deleniti soluta</P>
                    <button>LEARN MORE</button>
            </div>
            <div class="col">
                <h4>WHAT WE DO</h4>
                <P>Lorem ipsum,Fuga accusantium rerum ducimus harum autem saepe repudiandae deleniti soluta</P>
                <button>LEARN MORE</button>
            </div>
            <div class="col">
                <h4>WHERE WE WORK</h4>
                <P>Lorem ipsum,Fuga accusantium rerum ducimus harum autem saepe repudiandae deleniti soluta</P>
                <button>LEARN MORE</button>
                
            </div>
            
            
        </div>
        </div>

    </section>
    <section class="container text-center">
        <div class="row d-flex">
            <div class="col">
                <i class="fa-solid fa-check"></i>
                <h5>A GLOBAL VIEW</h5>
                <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Aspernatur ratione tenetur eius quia omnis magna</p>
            </div>
            <div class="col">
            <i class="fa-solid fa-check"></i>
            <h5>EXPERT LAWYERS</h5>
            <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Aspernatur ratione tenetur eius quia omnis magna</p>
            </div>
            <div class="col">
            <i class="fa-solid fa-check"></i>
            <h5>CLIENT LAWTERS</h5>
            <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Aspernatur ratione tenetur eius quia omnis magna</p>
            </div>
            <div class="col">
            <i class="fa-solid fa-check"></i>
            <h5>CLIENT FOCUS</h5>
            <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Aspernatur ratione tenetur eius quia omnis magna</p>
            </div>
        </div>

    </section>
    <section class="question p-5">
        <div class="container d-flex justify-content-between">
            <h2>QUESTION ABOUT A JUDICAL ISSUE? ASK OUR EXPERT</h2>
            <button>ASK AN EXPERT</button>

        </div>
    </section>
    
</main>

</template>
<style scoped>
.jambotron{
    background-image: url(../assets/img/video_law_home_preview.jpg);
    height: 30vh;
}

#introduction{
    background-color: rgb(245, 245, 245);
}

#introduction .col{
    background-color: white;
    padding: 30px;
    border-top: 3px solid rgb(84, 161, 153);
    border-left: 1px solid rgb(245, 245, 245);
    border-right: 1px solid rgb(245, 245, 245);
}

#introduction button{
    padding: 7px;
    border: 0;
    background-color: rgb(59, 66, 82);
    color: white;
}

.question{
    background-color: rgb(85, 160, 153);
    color: white;

}

button{
    border: 0;
    color: white;
    background-color: rgb(97, 172, 165);
    padding: 10px;
    font-size: 15px;
}
</style>