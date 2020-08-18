<template>
    <layout-1>
        <h1>coming from layout 0, line 1</h1>
        <div class="tw-bg-blue-200">
            <h1>coming from layout 0, line 2</h1>
            <nuxt/>
            <h1>coming from layout 0, line 3</h1>
        </div>
        <h1>coming from layout 0, line 4</h1>
    </layout-1>
</template>

<script>
import Layout1 from '~/layouts/test/nested_layouts/layout_1.vue';

export default {
    // layout: "default",
    components: {
        Layout1
    },
};
</script>
