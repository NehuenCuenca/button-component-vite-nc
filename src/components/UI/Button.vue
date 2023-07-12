<template>
    <!-- <button :class="stylesClasses"> -->
    <button>
        <i v-if="icon" class="material-symbols-outlined"> {{ icon }} </i>
        Default
    </button>
</template>

<script>
export default {
    name: 'Button',
    props: {
        /*'stylesClasses': {
            type: Array,
            required: false,
        },*/
        'icon': {
            type: String,
            required: false,
        }
    },
    setup() {
        return {}
    }
}
</script>

<style scoped>
button {
    cursor: pointer;
    font: 500 14px 'Noto Sans JP', sans-serif;
    transition: all .2s ease;
}

.default {
    width: 81px;
    height: 36px;
    border-radius: 6px;
    background-color: #E0E0E0;
    box-shadow: 0px 2px 3px 0px #33333333;
    border: none;
}

.default:hover,
.default:focus,
.default.on-hover,
.default.on-focus {
    background-color: #AEAEAE;
}


.outline {
    width: 88px;
    height: 36px;
    border-radius: 6px;
    border: 1px solid #3D5AFE;
    color: #3D5AFE;
}

.outline:hover,
.outline:focus,
.outline.on-hover,
.outline.on-focus {
    background-color: #eaefff;
}

.only-text {
    width: 88px;
    height: 36px;
    border-radius: 6px;
    border: none;
    color: #3D5AFE;
    background-color: transparent;
}

.only-text:hover,
.only-text:focus,
.only-text.on-hover,
.only-text.on-focus {
    background-color: #eaefff;
}

.disable-shadow {
    width: 81px;
    height: 36px;
    border-radius: 6px;
    background-color: #3D5AFE;
    color: #FFFFFF;
    box-shadow: 0px 2px 3px 0px #33333333;
    border: none;
}

.disabled {
    width: 81px;
    height: 36px;
    border-radius: 6px;
    background-color: #E0E0E0;
    color: #9E9E9E;
    border: none;
}

.disabled.only-text {
    background-color: transparent;
}

i {
    font-style: normal;
    font-size: 1.2rem;
}

.w-icon {
    width: 105px;
    height: 36px;
    border-radius: 6px;
    background-color: #3D5AFE;
    color: #FFFFFF;
    border: none;
    display: flex;
    align-items: center;
    justify-content: space-around;
}

.w-icon.startIcon {
    flex-direction: row;
}

.w-icon.endIcon {
    flex-direction: row-reverse;
}



.s-sm {
    width: 73px;
    height: 32px;
}

.s-md {
    width: 81px;
    height: 36px;
}

.s-lg {
    width: 93px;
    height: 42px;
}

.borderless {
    border: none;
}

.shadow {
    box-shadow: 0px 2px 3px 0px #33333333;
}

.b-round-6 {
    border-radius: 6px;
}

.txt-white {
    color: #FFFF;
}

.txt-dark {
    color: #3F3F3F;
}

.bg-default {
    background-color: #E0E0E0;
}

.bg-primary {
    background-color: #2962FF;
}

.bg-secondary {
    background-color: #455A64;
}
.bg-secondary {
    background-color: #455A64;
}
.bg-danger {
    background-color: #D32F2F;
}

.bg-default.on-focus,
.bg-default.on-hover,
.bg-default:hover,
.bg-default:focus {
    background-color: #AEAEAE;
}

.bg-primary.on-focus,
.bg-primary.on-hover,
.bg-primary:hover,
.bg-primary:focus {
    background-color: #0039CB;
}

.bg-secondary.on-focus,
.bg-secondary.on-hover,
.bg-secondary:hover,
.bg-secondary:focus {
    background-color: #1C313A;
}

.bg-danger.on-focus,
.bg-danger.on-hover,
.bg-danger:hover,
.bg-danger:focus {
    background-color: #9A0007;
}

</style>