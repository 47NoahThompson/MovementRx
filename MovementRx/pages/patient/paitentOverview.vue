<template>
    <div class="body">
        <div>
            <div style="height: 75px;"><Navigation pageTitle="Patient Overview"></Navigation></div>
        </div>

        <div class="grid-parent">
            <div class="grid1">
            <div name="streak" class="circle">
                <div>
                    <h1 class="center">#</h1>
                    <h1 class="center">Day Streak</h1>
                </div>
            </div>
            </div>
            
            <div class="grid2">
            <div name="notes" class="notes">
                <div class="notes-text">
                    <h1>Notes</h1>
                    <p>Words go here</p>
                </div>
            </div>
            </div>

            <div class="grid3">
            <div name="exercises" class="exercises">
                <div class="exercises-text">
                    <h1>Exercises</h1>
                    <ul>
                        <li>Exercise 1</li>
                        <li>Exercise 2</li>
                        <li>Exercise 3</li>
                    </ul>
                </div>
            </div>
            </div>

            <div class="grid4">
            <div name="readings" class="readings">
                <div class="readings-text">
                    <h1>Readings</h1>
                    <ul>
                        <li>Reading 1</li>
                        <li>Reading 2</li>
                        <li>Reading 3</li>
                    </ul>
                </div>
            </div>
            </div>
        </div>

        <div name="startExercise">
            <button class="start-exercise-btn">Start Exercise</button>
        </div>
    </div>

</template>

<script>
export default {
    setup () {
        

        return {}
    }
}
</script>

<style scoped>
p {
    font-size: x-large;
}

ul {
    font-size: x-large;
}

.circle {
    background: #0665AA;
    aspect-ratio : 1 / 1;
    height: 80%;
    margin: auto;
    position: relative;
    top: 50%; left: 50%;
    transform: translate(-50%,-50%);
    border-radius: 50%;
    display: flex;
    justify-content: center;
    text-align: center;
    align-items: center;
    color: antiquewhite;
}

.center {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    text-align: center;
}

.notes {
    background: #BDE3FF;
    height: 100%;
    border-radius: 25px;
}

.notes-text {
    padding-left: 2%;
    padding-right: 2%;
}

.exercises {
    background: #BDE3FF;
    height: 100%;
    border-radius: 25px;
}

.exercises-text {
    padding-left: 2%;
    padding-right: 2%;
}

.readings {
    background: #0665AA;
    height: 100%;
    border-radius: 7.5px;
}

.readings-text {
    padding-left: 2%;
    padding-right: 2%;
    color: antiquewhite;
}

.start-exercise-btn {
    margin-top: 15px;
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

.grid-parent {
    display: grid;
    height: 75vh; /* 100% of the viewport height */
    width: 100vw;  /* 100% of the viewport width */
    grid-template-columns: repeat(3, 1fr);
    grid-template-rows: repeat(2, 1fr);
    grid-column-gap: 0px;
    grid-row-gap: 0px;
}

.grid1 {
    grid-area: 1 / 1 / 2 / 2;
    margin-left: auto;
    margin-right: auto;
}

.grid2 {
    grid-area: 1 / 2 / 2 / 4;
    margin: 1%;
}

.grid3 {
    grid-area: 2 / 1 / 3 / 3;
    margin: 1%;
}

.grid4 {
    grid-area: 2 / 3 / 3 / 4;
    margin: 1%;
}

</style>