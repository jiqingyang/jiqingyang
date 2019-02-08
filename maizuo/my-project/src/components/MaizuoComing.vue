<template>
    <div>
      <heads></heads>
      <change></change>
      <coming></coming>
      <foot></foot>
    </div>
</template>
<script>
import Change from '@/components/Change';
import Heads from '@/components/Header'
import Coming from '@/components/Coming'

import Foot from '@/components/Footer'

export default {
     components:{Heads,Change,Coming,Foot}
}
</script>
