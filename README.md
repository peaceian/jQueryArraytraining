# jQuery Array training
This training is using jQuery to contribute the Array() to random change the images.<br>
Making an 1 dimension array to set images Array = ['','','',''] <br>
<script>
function fRandomBy(under,over){//取隨機參數，範圍0-4//function可以搬到最後，不影響
                switch(arguments.length){//switch，if/else條件太多時，可使用switch case敘述一連串的條件判斷與回應。
                    case 1: return parseInt(Math.random()*under+1);//取整數，下限+1
                    case 2: return parseInt(Math.random()*(over-under+1)+under);//(上限-下限+1)+下限
                    default: return 0;//第0張
                }
            }
</script>
