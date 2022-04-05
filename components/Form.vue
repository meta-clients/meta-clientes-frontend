<template>
    <div class="form">
      <form action="post">
        <div :key="input" v-for="input in inputs" class="input__group">
            <label class="input__group--label" :for="input.name">{{ input.label }}</label>
            <input class="input__group--input" :type="input.type" :placeholder="input.placeholder" :name="input.name" :id="input.id">
        </div>
      </form>
    </div>
</template>

<script>
export default {
    props: {
      inputs: {
        required: true,
        type: String,
      }
    }
}
</script>

<style>

</style>
