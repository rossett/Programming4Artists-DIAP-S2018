var ball = {
    x: 10,
    y: 10,
    w: 50,
    h: 50,
    xsp: 2,
    ysp: 4,

    move: function () {
        if (ball.x >= width || ball.x <= 0) {
            ball.xsp = ball.xsp * -1;
        }
        if (ball.y >= height || ball.y <= 0) {
            ball.ysp = ball.ysp * -1;
        }
        ball.x = ball.x + ball.xsp;
        ball.y = ball.y + ball.ysp;
    },
    drawball: function () {
        fill(0, 0, 255);
        ellipse(ball.x, ball.y, ball.w, ball.h);
    }
};
var ball2 = {
    x: 15,
    y: 15,
    w: 50,
    h: 50,
    xsp: 3,
    ysp: 5,

    move: function () {
        if (ball2.x >= width || ball2.x <= 0) {
            ball2.xsp = ball2.xsp * -1;
        }
        if (ball2.y >= height || ball2.y <= 0) {
            ball2.ysp = ball2.ysp * -1;
        }
        ball2.x = ball2.x + ball2.xsp;
        ball2.y = ball2.y + ball2.ysp;
    },
    drawball: function () {
        fill(0, 0, 255);
        ellipse(ball2.x, ball2.y, ball2.w, ball2.h);
    }
};



function setup() {
    createCanvas(windowWidth, windowHeight);
}

function draw() {
    background(255);
    ball.move();
    ball.drawball();
    ball2.move();
    ball2.drawball();

}

function mousePressed() {
    ball2.xsp = ball2.xsp * 2;
}
