<template>
    <div class="container">
        <div class="row justify-content-center">
            <div class="col-md-3 mt-5">
                <div class="card text-white bg-dark">
                    <div class="card-header">Example Component</div>

                    <div class="card-body">
                        I'm an example component.

                        <div class="input-group">
                            <div class="custom-file">
                                <input type="file" class="custom-file-input" id="inputGroupFile04">
                                <label class="custom-file-label" for="inputGroupFile04">Choose file</label>
                            </div>
                            <div class="input-group-append">
                                <button class="btn btn-outline-secondary" type="button">Button</button>
                            </div>
                        </div>

                        {{ text }}
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        data: function () {
            return {
                text: ''
            }
        },

        mounted() {
            console.log('Component mounted.')
        }
    }
</script>
