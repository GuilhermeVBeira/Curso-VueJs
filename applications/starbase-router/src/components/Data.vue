<template>
<div class="">
    Type: {{type}}
</div>
</template>

<scritp>
export default {
    data() {
        return {
            type: this.$route.params.type
        }
    }
}
</scritp>