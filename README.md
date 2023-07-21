# assignment2-Pattela
# Rithesh Pattela
## My favourite place is Matahari Tulamben Resort, Bali
<br> I really like **scuba diving** and matahari island is the most **amazing** place for providing most amazing diving spots

---

# Direction for going to Matahari Tulamben Resort from Maryville
1. Travel to kansas city by cab.
2. Arrive at San Francisco city airport by a flight.
3. Book flight to Ngurah Rai International Airport from san francisco.
4. Reach appropriate terminals by air train.
   1. Get boarding pass.
   2. Have security check done.
   3. Board appropriate flight.
5. Book a taxi to reach matahari tulamben resort.

* Currency conversion from usd to Indonesian rupiah.
* A good quality camera to capture pics of asthetic scenaries.
* List of places to visit like
  * the amazing town of Ubud
  * Sanur
  * Uluwatu
* First Aid Kit/medicines
* Appropriate cosmetics before going to beach like sunscreen lotions etc. 

---

# Beverages and food items
  The following table shows the best food and drinks available in different locations near me at the best price.<br> Please refer to this table and choose what you want.

   | Food/Drink   | Location  | Price |
   | ----------   | --------  | ----- |
   |   cappuccino | Starbucks |  2$   |
   |   Oreo Shake | Mooyah    |  4$   |
   |   Pizza      | Dominos   |  6$   |
   |   Pad Thai   | bai tong  |  12$  |

---

# Pithy Quotes

> You have brains in your head. You have feet in your shoes. You can steer yourself any direction you choose. You're on your own. And you know what you know. And YOU are the one who'll decide where to go.<br>
― *Dr. Seuss*

> It is never too late to be what you might have been.
― *George Eliot*

---

# Geometry  Elementary/Polygons 
> Using a given a set of ordered non-collinear points, a simple polygon can be formed and its shape is dependent on the sorting method used. To form such simple polygons with a given set of plane points, the points must first be ordered in one direction (typically, the x-axis is used). The first three points in the set are used to form an initial polygon. Based on the formed polygon, new polygons can be iteratively formed by inserting the first point of from among the remaining set of points, depending on line visibility from that point. This process is carried out until all the points are inserted into the polygon. In this study, we generated 20, 50, and 80 plane points and used the proposed method to construct polygons. 

[Source](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0230342)

```
double area(const vector<point>& fig) {
    double res = 0;
    for (unsigned i = 0; i < fig.size(); i++) {
        point p = i ? fig[i - 1] : fig.back();
        point q = fig[i];
        res += (p.x - q.x) * (p.y + q.y);
    }
    return fabs(res) / 2;
}
```

[Source](https://cp-algorithms.com/geometry/area-of-simple-polygon.html)

[Click here to see about me](https://github.com/S545395/assignment2-dommety/blob/main/AboutMe.md)
