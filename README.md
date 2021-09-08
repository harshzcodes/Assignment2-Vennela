# Assignment2-Vennela
# Sai Harsha Vennela
### Triund
 Triund is one of the **trekking** place located in India.We get to trek upto 5 miles and we get see the beautiful **sunset** on the way to moutain top. In the night we can see the **milkyway** with our naked eye.

 ---
 # Directions to Triund
 ### Since Triund is located in an entirely different country which is India, the only mode of transportation possible is **Airways**.
1. From Maryville to Delhi,India.

    1. As this is an international travel, we should be travelling to an international airport from Maryville.
    1. Travel from Maryville to Kansas city (MCI) airport by road.
    1. From Kansas Citry (MCI) to Chicago (ord) airport by taking a flight and travel through airways
    1. And, from Chicago to Delhi there will be direct flights available.
    1.  By this point you will be reaching Delhi.
1.  From Delhi to Himachal Pradesh.
    1. Since Triund is located in state of Himachal Pradesh, the only means of transportation is by road as it is a Mountain area.
    1. Travel by Delhi metro services from Delhi international airport to Delhi Bus station.
    1. From Delhi bus station, there will be plenty busses available to travel to Triund.
    1. It is a total of 8 hours road journey by bus from Delhi to Triund approximately.
- List of items to be brought to experience maximum enjoyment.
    - Carry a sleeping bag along with a camping tent
    - Carry a jacket and a sweater
    - Few water bottles, proteine bars and energy drinks to refuel your energy on your way while terkking.
    - Carry a torch light which is helpful incase of light fall while you trekk.
    
[Click here to know about me.](AboutMe.md)

---
# Must Try Foods/Drinks
Drinks I would suggest as must try :

| Food/Drink | Location | Price
|--- | ----| --- |
| Roasted Shrimp Rice | Spice Kitchen, Hyderabad | $3.21
| Deep Dish Pizza | Rosati's Pizza, Chicago | $4.69
| Cappuccino Frappe | Starbucks | $3.66
| Cookies and Cream Ice Cream Oreo | Walmart | $2.98

---
# Quotes I like
> You can become knowledgeable from others knowledge But you can not become wise from others wisdom. *-Michel de Montaigne*

> Be the change that you wish to see in the world.*-Mahatma Gandhi*
---
# Basic Geometry
> Geometry is a branch of mathematics that studies the sizes, shapes, positions angles and dimensions of things. Flat shapes like squares, circles, and triangles are a part of flat geometry and are called 2D shapes.
[-Click here for source link.](https://www.splashlearn.com/math-vocabulary/geometry/geometry)

Linear Operations on 2D points :
~~~ 
struct point2d {
    ftype x, y;
    point2d() {}
    point2d(ftype x, ftype y): x(x), y(y) {}
    point2d& operator+=(const point2d &t) {
        x += t.x;
        y += t.y;
        return *this;
    }
    point2d& operator-=(const point2d &t) {
        x -= t.x;
        y -= t.y;
        return *this;
    }
    point2d& operator*=(ftype t) {
        x *= t;
        y *= t;
        return *this;
    }
    point2d& operator/=(ftype t) {
        x /= t;
        y /= t;
        return *this;
    }
    point2d operator+(const point2d &t) const {
        return point2d(*this) += t;
    }
    point2d operator-(const point2d &t) const {
        return point2d(*this) -= t;
    }
    point2d operator*(ftype t) const {
        return point2d(*this) *= t;
    }
    point2d operator/(ftype t) const {
        return point2d(*this) /= t;
    }
};
point2d operator*(ftype a, point2d b) {
    return b * a;
}
 ~~~
[Click here for more.](https://cp-algorithms.com/geometry/basic-geometry.html)





