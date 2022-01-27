<template>
    <footer>
        <footer-services/>
        <footer-list/>
        <footer-contact/>
    </footer>
</template>

<script>
import FooterServices from './FooterServices.vue'
import FooterList from './FooterList.vue'
import FooterContact from './FooterContact.vue'
export default {
    components: {
        FooterServices,
        FooterList,
        FooterContact
    }
}
</script>

<style lang="scss" scoped>

</style>