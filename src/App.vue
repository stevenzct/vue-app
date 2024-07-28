<template>
  <div>
    <form-one></form-one>
    <form-two></form-two>
  </div>
</template>

<script>
  import formOne from './components/formOne.vue';
  import formTwo from './components/formTwo.vue';


  export default {
    components: {
        'form-one': formOne,
        'form-two': formTwo
    },
    data () {
        return {
            component: 'form-one'
        }
    },
    methods: {
        handleSubmit: function(){
            alert('thanks for submitting');
        }
    }
}
</script>







