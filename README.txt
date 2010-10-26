demo:

http://dl.dropbox.com/u/268240/googleCode/jquery-ui-swipable/index.html


usage:

$(element).swipable();
$(element).bind('swipe.right', function(){
    alert('right swiped');
});
$(element).bind('swipe.left', function(){
    alert('left swiped');
});
$(element).bind('swipe.top', function(){
    alert('top swiped');
});
$(element).bind('swipe.bottom', function(){
    alert('bottom swiped');
});


options:

$(element).swipable({
    preventDefault:false, // turn false to allow native scroll
    distance:150 // px threshold to invoke swipe events
});


depends on:

jQuery 1.4.3
jQuery UI 1.8.5
jQuery UI Widget 1.8.5
