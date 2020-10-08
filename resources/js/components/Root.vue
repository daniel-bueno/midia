<template>
    <div class="container">
        <div class="row justify-content-center">
            <div class="col-md-3 mt-5">
                <div class="card text-white c-black mh-400">
                    <div class="card-header text-center">

                    </div>
                    <div class="card-body">

                    </div>
                </div>
            </div>
            <div class="col-md-3 mt-5">
                <div class="card text-white c-black" style="min-height: 270px">
                    <div class="card-header text-center">

                    </div>
                    <div class="card-body">

                    </div>
                </div>

                <div class="card text-white c-black" style="min-height: 100px; margin-top: 30px">
                    <div class="card-header text-center">

                    </div>
                    <div class="card-body">

                    </div>
                </div>
            </div>
            <div class="col-md-3 mt-5">
                <div class="card text-white c-black mh-400">
                    <div class="card-header text-center">
                        <i class="fa fa-2x fa-stream mb-2 mt-3 color-fa-midia"></i>
                        <h5 class="text-bold">Lista de Arquivos</h5>
                    </div>
                    <div class="card-body">
                        <ul class="list-group list-group-flush ft-small">
                            <li class="list-group-item li-black">
                                <span class="icon-midia">
                                    <i class="far fa-file"></i>
                                </span>

                                Cras justo odio

                                <div style="float: right; margin: -5px -15px;">
                                    <button class="btn btn-sm btn-outline-success">
                                        <i class="fas fa-play"></i>
                                    </button>
                                    <button class="btn btn-sm btn-outline-danger btn-">
                                        <i class="fas fa-times"></i>
                                    </button>
                                </div>
                            </li>
                            <li class="list-group-item mb-0 li-black">
                                <span class="icon-midia">
                                    <i class="far fa-file"></i>
                                </span>
                                Dapibus ac facilis
                                <div style="float: right; margin: -5px -15px;">
                                    <button class="btn btn-sm btn-outline-success">
                                        <i class="fas fa-play"></i>
                                    </button>
                                    <button class="btn btn-sm btn-outline-danger">
                                        <i class="fas fa-times"></i>
                                    </button>
                                </div>
                            </li>
                            <li class="list-group-item li-black">
                                <span class="icon-midia">
                                    <i class="far fa-file"></i>
                                </span>
                                Morbi leo risus
                                <div style="float: right; margin: -5px -15px;">
                                    <button class="btn btn-sm btn-outline-success">
                                        <i class="fas fa-play"></i>
                                    </button>
                                    <button class="btn btn-sm btn-outline-danger">
                                        <i class="fas fa-times"></i>
                                    </button>
                                </div>
                            </li>
                            <li class="list-group-item li-black">
                                <span class="icon-midia">
                                    <i class="far fa-file"></i>
                                </span>
                                Porta ac consect
                                <div style="float: right; margin: -5px -15px;">
                                    <button class="btn btn-sm btn-outline-success">
                                        <i class="fas fa-play"></i>
                                    </button>
                                    <button class="btn btn-sm btn-outline-danger">
                                        <i class="fas fa-times"></i>
                                    </button>
                                </div>
                            </li>
                            <li class="list-group-item li-black">
                                <span class="icon-midia">
                                    <i class="far fa-file"></i>
                                </span>
                                Vestibulum at eros
                                <div style="float: right; margin: -5px -15px;">
                                    <button class="btn btn-sm btn-outline-success">
                                        <i class="fas fa-play"></i>
                                    </button>
                                    <button class="btn btn-sm btn-outline-danger">
                                        <i class="fas fa-times"></i>
                                    </button>
                                </div>
                            </li>
                        </ul>
                    </div>
                </div>
            </div>
            <div class="col-md-3 mt-5">
                <div class="card text-white c-black mh-400">
                    <div class="card-header text-center">
                        <i class="fa fa-2x fa-folder mb-2 mt-3 color-fa-midia"></i>
                        <h5 class="text-bold">Adicionar Mídia</h5>
                        <small class="label-extens">Extensões permitidas:</small>
                        <div class="mt-2">
                            <small class="badge-extens">.mp3</small>
                            <small class="badge-extens">.mp4</small>
                            <small class="badge-extens">.mov</small>
                        </div>
                        <div class="mt-2">
                            <small class="badge-extens">.png</small>
                            <small class="badge-extens">.jpeg</small>
                            <small class="badge-extens">.txt</small>
                        </div>
                    </div>
                    <div class="card-body">
                        <div class="row mt-3 mb-5">
                            <div class="col-md-12">
                                <div class="input-group">
                                    <input type="text" class="form-control" placeholder="Incluir Arquivo" readonly>
                                    <div class="input-group-append">
                                        <label class="btn btn-outline-secondary">
                                            <input type="file" style="display: none">
                                            <i class="fa fa-1x fa-upload"></i>
                                        </label>
                                    </div>
                                </div>
                            </div>
                            <div class="col-md-12 mt-3">
                                <button type="button" class="btn btn-primary btn-upload-m w-100">Upload</button>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>

    import "@fortawesome/fontawesome-free/js/all";

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


<style>

    body {
        color: #fff;
        background-color: #171717;
    }

    .c-black {
        background-color: black;
        border-radius: 20px
    }

    .mh-400 {
        min-height: 400px;
    }

    .ft-small{
        font-size: 80%;
    }

    .color-fa-midia {
        color: #4136F1
    }

    /**
     * Listar Arquivos
     *
     */
    .li-black {
        background-color: black;
    }

    .icon-midia {
        margin-right: 5px;
        margin-left: -15px;
        padding: 7px 10px;
        border-radius: 10px;
        border: 1px solid #6c757d
    }

    /**
     * Adicionar Mídia
     *
     */
    .label-extens {
        color: rgba(243, 122, 89, 1);
    }

    .badge-extens {
        border: 1.5px solid rgba(134, 67, 255, 1);
        border-radius: 15px;
        padding: 2px 11px;
        margin: 3px;
    }

    .btn-upload-m {
        background: linear-gradient(to left, #8643FF 0%, #4136F1 100%);
        border: 1px solid #4136F1;
    }
</style>
