<template>

</template>

<script>
      var vue_det = new Vue({
            el: '#intro',
            data: {
               timestamp: ""
            },
            created() {
                setInterval(this.getNow, 1000);
            },
            methods: {
                getNow: function() {
                    const today = new Date();
                    const date = today.getFullYear()+'-'+(today.getMonth()+1)+'-'+today.getDate();
                    const time = today.getHours() + ":" + today.getMinutes() + ":" + today.getSeconds();
                    const dateTime = date +' '+ time;
                    this.timestamp = dateTime;
                }
            }
         });
export default{
name : "date",
}
</script>