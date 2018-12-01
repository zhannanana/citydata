<template>
    <div class="tnavbar">
        <nav class="navbar navbar-default navbar-fixed-top">
            <div class="container">
                <div class="navbar-header">
                    <button type="button" class="navbar-toggle collapsed" data-toggle="collapse" data-target="#navbar" aria-expanded="false" aria-controls="navbar">
                        <span class="sr-only">Toggle navigation</span>
                        <span class="icon-bar"></span>
                        <span class="icon-bar"></span>
                        <span class="icon-bar"></span>
                    </button>
                    <a class="navbar-brand" href="#">智慧城市计算数据展示平台</a>
                </div>
                <div id="navbar" class="navbar-collapse collapse">
                    <ul class="nav navbar-nav navbar-right">
                        <li class="active"><a href="traffic-index.html">{{traffic}}<span class="sr-only">(current)</span></a></li>
                        <li><a href="../meteorology/meteorology-index.html">{{weather}}</a></li>
                        <li><a href="../hydrology/hydrology-index.html">{{hydrology}} </a></li>
                    </ul>
                </div><!--/.nav-collapse -->
            </div>
        </nav>
    </div>
</template>


<script>
    export default {
        name: 'tnavbar',
        data () {
            return {
                msg: '欢迎来到菜鸟教程！'
            }
        }
    }
</script>