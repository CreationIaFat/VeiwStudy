<div id="fruts-list">
<h1>フルーツ一覧</h1>
<script src="https:unpkg.com/vue@2.5.17"></script>
<div id="#fruts-list">
    <fruts-list-title></fruts-list-title>
</div>
<script>
Vue.compornent('fruts-list-title',{
    template:'<h1>フルーツ一覧</h1>'
})
new Vue({
    el:'#fruts-list'
})
</script>
