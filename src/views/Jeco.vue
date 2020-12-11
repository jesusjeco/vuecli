<template>
    <div>
        This is the JECO View
        <div class="container">
            <div class="row">
                <div class="col-12">
                    <JecoComponent></JecoComponent>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
import JecoComponent from '../components/JecoComponent';

    export default {
        name: 'Jeco',
        components: {
            JecoComponent
        }
    }
</script>

<style scoped>

</style>