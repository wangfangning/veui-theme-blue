<template>
    <article>
        <H1>bi字体规范</H1>
        <div>
            <label>一级A</label>
            <span class="veui-font-level-1a name">流程信息管理</span>
            <span class="class-name">类名:veui-font-level-1a</span>
        </div>
        <div>
            <label>一级B</label>
            <span class="veui-font-level-1b name">流程信息管理</span>
            <span class="class-name">类名:veui-font-level-1b</span>
        </div>
        <div>
            <label>二级A</label>
            <span class="veui-font-level-2a name">流程信息管理</span>
            <span class="class-name">类名:veui-font-level-2a</span>
        </div>
        <div>
            <label>二级B</label>
            <span class="veui-font-level-2b name">流程信息管理</span>
            <span class="class-name">类名:veui-font-level-2b</span>
        </div>
        <div>
            <label>二级C</label>
            <span class="veui-font-level-2c name">流程信息管理</span>
            <span class="class-name">类名:veui-font-level-2c</span>
        </div>
        <div>
            <label>二级D</label>
            <span class="veui-font-level-2d name">流程信息管理</span>
            <span class="class-name">类名:veui-font-level-2d</span>
        </div>
        <div>
            <label>二级E</label>
            <span class="veui-font-level-2e name">流程信息管理</span>
            <span class="class-name">类名:veui-font-level-2e</span>
        </div>
        <div>
            <label>三级A</label>
            <span class="veui-font-level-3a name">流程信息管理</span>
            <span class="class-name">类名:veui-font-level-3a</span>
        </div>
        <div>
            <label>三级B</label>
            <span class="veui-font-level-3b name">流程信息管理</span>
            <span class="class-name">类名:veui-font-level-3b</span>
        </div>
        <div>
            <label>三级C</label>
            <span class="veui-font-level-3c name">流程信息管理</span>
            <span class="class-name">类名:veui-font-level-3c</span>
        </div>
        <div>
            <label>三级D</label>
            <span class="veui-font-level-3d name">流程信息管理</span>
            <span class="class-name">类名:veui-font-level-3d</span>
        </div>
    </article>
</template>

<script>
    import bus from '../bus';
    import {Alert, Dialog} from 'veui';
    export default {
        name: 'Font',
        components: {
        },
        data() {
            return {};
        },
        methods: {
            close() {}
        },
        mounted() {}
    };
</script>

<style lang="less">
@import "~veui-theme-bi/lib.less";

    article {
        div {
            margin:10px;
            .class-name {
                color:@veui-brand-color;
                margin-left: 20px;
            }
            label {
                margin-right: 20px;
            }
            .name {
                width: 300px;
                display: inline-block;
            }
        }
    }
</style>
