jQuery(document).ready(function ($) {
    if (jQuery('.masonry').length > 0) {
        setTimeout(function () {
            jQuery('.masonry').imagesLoaded(function () {
                jQuery('.masonry').masonry({
                    columnWidth: 0,
                    itemSelector: '.blog_masonry_item',
                    isResizable: true
                });
            });
        }, 500);
    }
    $(document).on('click', '.social-component .bd-social-share', function (e) {
        e.preventDefault();
        if($(this).data('share') == 'facebook') {
            var $href = $(this).data('href');
            var $url = $(this).data('url');
            
            var $link = $href + '?u=' + $url;
            window.open($link,'targetWindow', 'width=800, height=400', 'toolbar=no', 'location=0', 'status=no', 'menubar=no', 'scrollbars=yes', 'resizable=yes');
        }
        
        if($(this).data('share') == 'linkedin') {
            var $href = $(this).data('href');
            var $url = $(this).data('url');
            
            var $link = $href + '?url=' + $url;
            window.open($link,'targetWindow', 'width=800, height=400', 'toolbar=no', 'location=0', 'status=no', 'menubar=no', 'scrollbars=yes', 'resizable=yes');
        }
        
        if($(this).data('share') == 'twitter') {
            var $href = $(this).data('href');
            var $text = $(this).data('text');
            var $url = $(this).data('url');
            
            var $link = $href + '?text=' + $text + '&url=' + $url;
            window.open($link,'targetWindow', 'width=800, height=400', 'toolbar=no', 'location=0', 'status=no', 'menubar=no', 'scrollbars=yes', 'resizable=yes');
        }
        
        if($(this).data('share') == 'pinterest') {
            var $href = $(this).data('href');
            var $url = $(this).data('url');
            var $media = $(this).data('media');
            var $description = $(this).data('description');
            
            var $link = $href + '?url=' + $url + '&media=' + $media + '&description=' + $description;
            window.open($link,'targetWindow', 'width=800, height=400', 'toolbar=no', 'location=0', 'status=no', 'menubar=no', 'scrollbars=yes', 'resizable=yes');
        }
        
    });
    bd_get_boxy_clean_height();
});
jQuery(window).resize(function () { 
    bd_get_boxy_clean_height();
});

function bd_get_boxy_clean_height() {
    var divs = jQuery(".boxy-clean li.blog_wrap").not('.first_post');
    if (jQuery(window).width() > 980) {
        var column = 4;
        if (divs.hasClass('three_column')) {
            column = 3;
        } else if (divs.hasClass('two_column')) {
            column = 2;
        } else if (divs.hasClass('one_column')) {
            column = 1;
        }
    } else if (jQuery(window).width() <= 980 && jQuery(window).width() > 720) {
        var column = 4;
        if (divs.hasClass('three_column_ipad')) {
            column = 3;
        } else if (divs.hasClass('two_column_ipad')) {
            column = 2;
        } else if (divs.hasClass('one_column_ipad')) {
            column = 1;
        }
    } else if (jQuery(window).width() <= 720 && jQuery(window).width() > 480) {
        var column = 4;
        if (divs.hasClass('three_column_tablet')) {
            column = 3;
        } else if (divs.hasClass('two_column_tablet')) {
            column = 2;
        } else if (divs.hasClass('one_column_tablet')) {
            column = 1;
        }
    } else if (jQuery(window).width() <= 480) {
        var column = 4;
        if (divs.hasClass('one_column_mobile')) {
            column = 3;
        } else if (divs.hasClass('two_column_mobile')) {
            column = 2;
        } else if (divs.hasClass('three_column_mobile')) {
            column = 1;
        }
    }
    jQuery(".boxy-clean li.blog_wrap").removeAttr('style');

    for (var i = 0; i < divs.length; i += column) {
        var heights = jQuery(".boxy-clean li.blog_wrap").not('.first_post').slice(i, i + column).map(function () {
            return jQuery(this).height();
        }).get();
        var maxHeight = Math.max.apply(null, heights);
        if (screen.width > 640) {
            jQuery(".boxy-clean li.blog_wrap").not('.first_post').slice(i, i + column).css('height', maxHeight + 150);
        }
    }
}
