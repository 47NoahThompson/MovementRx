<template>
    <div>
        <h1>LogIn Page</h1>

        <h2>Patient</h2>
        <RouterLink to="./patient/paitentOverview">Patient Overview</RouterLink><br />
        <RouterLink to="./patient/myReadings">My Readings</RouterLink><br /><br />
        <h3>Exercise</h3>
        <RouterLink to="./patient/excersice/exercises">Exercises</RouterLink><br />
        <RouterLink to="./patient/excersice/exerciseEnd">Exercise End</RouterLink><br /><br />
        <h2>Physo</h2>
        <RouterLink to="./physio/patientSearch">Patient Search</RouterLink><br />
        <RouterLink to="./physio/patientView">Patient View</RouterLink><br /><br />
        <h2>Readings</h2>
        <RouterLink to="./readings/article">Article</RouterLink><br />
        <RouterLink to="./readings/articleSearch">Article Search</RouterLink><br />
        <RouterLink to="./readings/newArticle">New Article</RouterLink><br /><br />
    
        <h2>Componets</h2>
        <RouterLink to="./componentTest">Component Test</RouterLink>
    </div>
</template>

<script>
export default {
    setup() {
        return {};
    }
}
</script>

<style lang="scss" scoped>

</style>