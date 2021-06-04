# web-for-crush
$(document).ready(function() {
    // process bar
    setTimeout(function() {
        firstQuestion();
        $('.spinner').fadeOut();
        $('#preloader').delay(350).fadeOut('slow');
        $('body').delay(350).css({
            'overflow': 'visible'
        });
    }, 600);

})

function firstQuestion(){

    $('.content').hide();
    Swal.fire({
        title: 'He!',
        text: 'Tớ có điều này muốn hỏi cậu nhớ phải trả lời thật lòng nhaaa.',
        imageUrl: '../img/cuteCat.jpg',
        imageWidth: 300,
        imageHeight: 300,
        background: '#fff url("../img/iput-bg.jpg")',
        imageAlt: 'Custom image',
      }).then(function(){
        $('.content').show(200);
      })
}

 // switch button position
 function switchButton() {
    var audio = new Audio('../sound/duck.mp3');
    audio.play();
    var leftNo = $('#no').css("left");
    var topNO = $('#no').css("top");
    var leftY = $('#yes').css("left");
@@ -24,6 +42,8 @@ $(document).ready(function() {
}
// move random button póition
function moveButton() {
    var audio = new Audio('../sound/Swish1.mp3');
    audio.play();
    var x = Math.random() * 500;
    var y = Math.random() * 500;
    var left = x + 'px';
@@ -65,6 +85,8 @@ function textGenerate() {

// show popup
$('#yes').click(function() {
    var audio = new Audio('../sound/tick.mp3');
    audio.play();
    Swal.fire({
        title: 'Nói cho tớ lí do cậu thích tớ đi :vvvv',
        html: true,
@@ -89,10 +111,14 @@ $('#yes').click(function() {
        if (result.value) {
            Swal.fire({
                width: 900,
                confirmButtonText: 'Yêuuuuuu <3',
                confirmButtonText: 'Okiiiii lun <3',
                background: '#fff url("../img/iput-bg.jpg")',
                title: 'Biết mà! Tối nay tớ qua đón cậu đi chơi nhaaaaaaaaa :v',
                title: 'Tớ biết mà ^^ Yêu cậu 300.000',
                text: "Tối nay tớ qua đón cậu đi chơi nhaaaaaaaaa :v Còn giờ thì chờ gì nữa mà ko inbox cho tớ đi nàoooooo",
                confirmButtonColor: '#83d0c9',
                onClose: () => {
                    window.location = 'http://fb.com';
                  }
            })
        }
    })
