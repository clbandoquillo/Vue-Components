<template>
    <div class="container">
        <server-heading></server-heading>
        <hr>
        <div class="row">
            <server-list></server-list>
            <server-details></server-details>
        </div>
        <hr>
        <server-info></server-info>
    </div>
</template>

<script>
    import ServerList from './ServerList.vue';
    import PageInfo from './PageInfo.vue';
    import PageHeading from './PageHeading.vue';
    import ServerDetails from './ServerDetails.vue';

    export default{

        components: {
            'server-info' : PageInfo,
            'server-list' : ServerList,
            'server-heading' : PageHeading,
            'server-details' : ServerDetails
        }
    }

</script>

<style>

</style>
