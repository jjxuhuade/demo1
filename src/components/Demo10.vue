<template>
    <div class="component">
        <div class="container">
            <div class="row">
                <jj_layout1>
                    <h1 slot="header">这里可能是一个页面标题</h1>
                    <p>主要内容的一个段落。</p>
                    <p>另一个主要段落。</p>
                    <p slot="footer">这里有一些联系信息</p>
                </jj_layout1>
            </div>

        </div>
    </div>
</template>

<script>
  export default {
    data: function () {
      return {
      }
    },
    methods: {
    }
  }
</script>


