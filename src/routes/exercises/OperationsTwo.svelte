<!-- Data and Script -->
<script>
    import Navbar from "../../components/Navbar.svelte";
    import ExerciseContainer from "../../components/ExerciseContainer.svelte";
    let linkOne = "https://gist.github.com/rncyy/78ed20d7f2a44c038968b799720865ff";
    let linkTwo = "https://gist.github.com/rncyy/8650d897b4f2fe3dfccab9a0ac818d15";
</script>

<!-- HTML -->
<Navbar/>
<ExerciseContainer lessonTitle="Operations in Java 2" linkOne={linkOne} linkTwo={linkTwo} prevExercise="operations-1" nextExercise="decision-structure-1" isFirstExercise={false} isLastExercise={false}>
    <!-- question -->
    <div slot="question">
        Follow the specifications given for this exercise
    </div>
    <div slot="desc">
        <ol class="work-sans">
            <li>Make use of the previous program you have created</li>
            <li>Instead of computing the result in the <code>println()</code> statement, create separate variables for the addition, subtraction, multiplication, and division.</li>
            <li>Print all the newly created result variables</li>
        </ol>
    </div>
</ExerciseContainer>
<!-- Scope Styles -->
<style>

</style>