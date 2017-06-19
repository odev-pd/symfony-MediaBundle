# MediaBundle


css required : 

    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css">
    <link rel="stylesheet" href="{{ asset('bundles/artgrismedia/css/media.css') }}">
    <link rel="stylesheet" href="{{ asset('bundles/artgrisfilemanager/libs/blueimp-file-upload/css/jquery.fileupload.css') }}">
          
 
js required :              
              
    <script   src="https://code.jquery.com/ui/1.12.1/jquery-ui.min.js" integrity="sha256-VazP97ZCwtekAsvgPBSUwPFKdrwD3unUfSGVYrahUqU=" crossorigin="anonymous"></script>
    <script src="{{ asset('bundles/artgrisfilemanager/libs/blueimp-file-upload/js/jquery.iframe-transport.js') }}"></script>
    <script src="{{ asset('bundles/artgrisfilemanager/libs/blueimp-file-upload/js/jquery.fileupload.js') }}"></script>
    <script src="{{ asset('bundles/artgrisfilemanager/libs/remarkable-bootstrap-notify/dist/bootstrap-notify.min.js') }}"></script>
    {% include '@ArtgrisMedia/assets/include_js.html.twig' %}