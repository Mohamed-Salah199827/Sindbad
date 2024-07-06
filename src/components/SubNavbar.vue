<template>
   <section class="subnav">

       <div>
        <p><i class="fa-sharp fa-solid fa-house" style=""></i> الصفحة الرئيسة</p> 
        <p class="arrow">></p>
        <p class="end">بوابة الدخول اللوجيستية</p>
       </div>
   </section>
    
</template>
<style lang="scss" scoped>
    .subnav{
        padding: 2vh;
        align-items: center;
        div{
            display: flex;
            .end{
                color:#9C9C9C;
                padding-right: 0px;
            }
        }
        p
        {
            padding-right: 6vw;
            color: var(--main-color);
            i{
                color: var(--main-color);
            }
      
           
        }
        .arrow{
            padding-right: 2px;
            padding-left: 2px;

            font-weight: bold;

        }
    }
</style>