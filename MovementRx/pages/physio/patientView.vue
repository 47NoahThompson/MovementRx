<template>
    <div>
        <h1>Patient Name</h1>

        <div name="PatientSearch">
            <div name="patientSearchBar"> <p>Search Bar</p> </div>
            <div name="patientSearchButton"> <button>Search</button> </div>
            <div name="newPatientButton"> <button>New Patient</button> </div>
        </div>

        <div name="PatientInfo">
            <div name="patientPhoto"> Patient Photo </div>
            <div name="patientDescription"> Patient Description</div>
        </div>

        <div name="PatientWeeks">
            <div name="previousWeek"> <p>←</p> </div>

            <div name="week">
                <div name="notes"> <p>Notes (Text Input)</p> </div>
                <div name="exercises"> <p>Exercises (Select)</p> </div>
                <div name="readings"> <p>Readings (Select)</p> </div>
            </div>
            
            <div name="nextWeek"> <p>→</p> </div>
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

<style lang="scss" scoped>

</style>