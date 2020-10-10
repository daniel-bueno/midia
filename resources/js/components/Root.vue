<template>
    <div class="container">
        <div class="row justify-content-center">

            <div class="col-md-3 mt-5">
                <div class="card text-white c-black mh-400">
                    <div class="card-body">
                        <div class="row">
                            <div class="col-md-12">
                                <div class="icon-img text-center">
                                    <i class="fa fa-video" style="color:#6c757d"></i>
                                </div>
                            </div>
                            <div class="col text-center mt-3">
                                <label for="customRange1" class="ft-small">Dapibus ac facilis</label>
                                <input type="range" id="customRange1" class="form-control-range" style="height: 4px" min="0" max="100">
                                <div class="mt-1">
                                    <div style="float: left; font-size: 10px">00:00</div>
                                    <div style="float: right; font-size: 10px">00:00</div>
                                </div>
                            </div>
                            <div class="col-md-12 text-center mt-3" style="margin-top: 5px;">
                                <button type="button" class="btn btn-xl btn-circle btn-primary btn-gdr-m">
                                    <i class="fa fa-play"></i>
                                </button>
                            </div>
                        </div>
                    </div>
                </div>
            </div>

            <div class="col-md-3 mt-5">
                <div class="card text-white c-black" style="min-height: 280px">
                    <div class="card-body">
                        <div class="row">
                            <div class="col-md-12">
                                <div class="icon-img text-center">
                                    <i class="fa fa-image" style="color:#6c757d"></i>
                                </div>
                            </div>
                            <div class="col text-center mt-3">
                                <button type="button" class="btn btn-sm btn-primary btn-gdr-m ft-small">Filtros</button>
                            </div>
                        </div>
                    </div>
                </div>

                <div class="card text-white c-black" style="min-height: 90px; margin-top: 30px">
                    <div class="card-body">
                        <div class="row">
                            <div class="col-md-2 pr-0">
                                <div class="icon-audio text-center">
                                    <i class="fa fa-microphone" style="color:#6c757d"></i>
                                </div>
                            </div>
                            <div class="col-md-8 pr-3" style="margin-top: -5px">
                                <label for="customRange1" class="ft-small">Cras justo odio</label>
                                <input type="range" id="customRange1" class="form-control-range" style="height: 4px" min="0" max="100">
                                <div class="mt-1">
                                    <div style="float: left; font-size: 10px">00:00</div>
                                    <div style="float: right; font-size: 10px">00:00</div>
                                </div>
                            </div>
                            <div class="col-md-2 pl-0" style="margin-top: 5px;">
                                <button type="button" class="btn btn-circle btn-primary btn-gdr-m">
                                    <i class="fa fa-play"></i>
                                </button>
                            </div>
                        </div>
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
                                <button type="button" class="btn btn-primary btn-gdr-m w-100">Upload</button>
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

    .icon-audio {
        border-radius: 15px;
        padding: 10px 0;
        border: 1px dashed #6c757d;
        margin: 0 -5px 0 -10px;
    }

    .icon-img {
        border-radius: 15px;
        padding: 85px 0;
        border: 1px dashed #6c757d;
        margin: 0;
    }

    .btn-circle.btn-xl {
        width: 70px;
        height: 70px;
        padding: 14px 26px;
        border-radius: 35px;
        font-size: 24px;
        line-height: 1.33;
    }

    .btn-circle {
        width: 35px;
        height: 35px;
        padding: 6px 0px;
        border-radius: 25px;
        text-align: center;
        font-size: 14px;
        line-height: 1.42857;
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

    .btn-gdr-m {
        background: linear-gradient(to left, #8643FF 0%, #4136F1 100%);
        border: 1px solid #4136F1;
    }
</style>
