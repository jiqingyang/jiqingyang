<template>
    <div>
      <heads></heads>
      <change></change>
      <move></move>
    

      <foot></foot>
    </div>
</template>
<script>
import Change from '@/components/Change';
import Heads from '@/components/Header'
import Move from '@/components/Move'
import Foot from '@/components/Footer'

export default {
     components:{Heads,Change,Move,Foot}
}
</script>
