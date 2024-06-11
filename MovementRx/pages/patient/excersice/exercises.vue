<template>
    <div>
        <div style="height: 75px;"><Navigation pageTitle="Exercise"></Navigation></div>
        
        <div>
            <p><span class="circle">2/4</span></p> 
        </div>

        <div class="exercise" style="text-align: center;">
            <video controls height="300" class="video-exercise"></video>

            <div name="setsAndReps" class="sets-reps"> <p>Sets and Reps</p> </div>

            <div name="description" class="description"> <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p> </div>
        </div>

        
    </div>

    <div name="nextExercise" style="padding-top: 2%;"> <button class="next-exercise-btn">Next Exercise</button> </div>
</template>

<script>
export default {
    setup () {
        

        return {}
    }
}
</script>

<style lang="scss" scoped>
.circle {
    margin-left: auto;
    background: #0665AA;
    aspect-ratio : 1 / 1;
    height: 75px;
    position: relative;
    border-radius: 50%;
    display: flex;
    justify-content: center;
    text-align: center;
    align-items: center;
    color: antiquewhite;
}

.exercise {
    margin-left: auto;
    margin-right: auto;
    width: 75%;
    height: 65vh;
    border-radius: 25px;
    background-color: #BDE3FF;
    padding-top: 2%;
    padding-bottom: 2%;
}

.video-exercise {
    height: 30%;
}

.next-exercise-btn {
    border-style: none;
    height: 50px;
    width: 150px;
    position: absolute;
    left: 50%;
    transform: translateX(-50%);
    border-radius: 7.5px;
    background-color: #0665AA;
    color: antiquewhite;
    font-size: large;
}

.sets-reps {
    text-align: center;
    margin: 0;
    padding: 0;
}

.description {
    position: relative;
    margin-left: auto;
    margin-right: auto;
    align-items: center;
    background-color: darkgray;
    border-radius: 15px;
    width: 80%;
    height: 55%;
    overflow: auto;
}
</style>