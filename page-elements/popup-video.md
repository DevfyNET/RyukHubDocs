# Popup Video

### [Popup Video Example](https://devfycr.com/ryukhub/element-popup-video.html)

```markup
<div class="row">
    <div class="col-md-12 mb-5 text-center">
        <!-- Button trigger modal -->
        <button type="button" class="btn btn-primary video-btn" data-toggle="modal" data-src="https://www.youtube.com/embed/Jfrjeg26Cwk" data-target="#modal-popup-video">
            Play Video 1 - autoplay
        </button>
    
        <!-- Button trigger modal -->
        <button type="button" class="btn btn-primary video-btn" data-toggle="modal" data-src="https://www.youtube.com/embed/IP7uGKgJL8U" data-target="#modal-popup-video">
            Play Video 2
        </button>
    
        <!-- Button trigger modal -->
        <button type="button" class="btn btn-primary video-btn" data-toggle="modal" data-src="https://www.youtube.com/embed/A-twOC3W558" data-target="#modal-popup-video">
            Play Video 3
        </button>
    
        <!-- Button trigger modal -->
        <button type="button" class="btn btn-primary video-btn" data-toggle="modal" data-src="https://player.vimeo.com/video/58385453?badge=0" data-target="#modal-popup-video">
            Play Vimeo Video
        </button>
    
        <!-- Modal -->
        <div class="modal fade" id="modal-popup-video" tabindex="-1" role="dialog" aria-labelledby="exampleModalLabel" aria-hidden="true">
            <div class="modal-dialog modal-dialog-video" role="document">
                <div class="modal-content">
                    <div class="modal-body modal-body-video">
                        <button type="button" class="close close-video" data-dismiss="modal" aria-label="Close">
                            <span aria-hidden="true">×</span>
                        </button>
                        <!-- 16:9 aspect ratio -->
                        <div class="embed-responsive embed-responsive-16by9">
                            <iframe class="embed-responsive-item" src="" id="video" allowscriptaccess="always" allow="autoplay"></iframe>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</div>
```

{% page-ref page="popup-video.md" %}



