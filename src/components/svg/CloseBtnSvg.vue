<template>
        <svg alt='cancel' version="1.1" id="CloseBtnSvg" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink"
            x="0px" y="0px" viewBox="0 0 38.2 38.2" style="enable-background:new 0 0 38.2 38.2;" xml:space="preserve">
            <g id="Group_470" transform="translate(-827.729 -473.706)">
                <g id="Group_440" transform="translate(635.21 575.488)">
                    <g id="Group_372" transform="translate(210.043 -107.993) rotate(45)">
                        <path id="Path_490" class="st0" d="M40.1,16.8H-2.1" />
                    </g>
                    <g id="Group_468" transform="translate(210.043 -107.993) rotate(45)">
                        <path id="Path_490-2" class="st0" d="M40.1,16.8H-2.1" />
                    </g>
                </g>
                <g id="Group_469" transform="translate(767.078 281.188) rotate(90)">
                    <g id="Group_372-2" transform="translate(210.043 -107.993) rotate(45)">
                        <path id="Path_490-3" class="st0" d="M42.2,18.9H0" />
                    </g>
                    <g id="Group_468-2" transform="translate(210.043 -107.993) rotate(45)">
                        <path id="Path_490-4" class="st0" d="M42.2,18.9H0" />
                    </g>
                </g>
            </g>
        </svg>
</template>

<script>
export default {
    name: "closeBtn",
    props: ["color"],
    emits: []
}
</script>

<style>
.st0 {
    fill: none;
    stroke: v-bind("color");
    stroke-width: 8;
    stroke-linecap: round;
}

</style>