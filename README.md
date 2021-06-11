A simple command-line application.

### Dart Apprentice solutions

#### Chapter 2

```
import 'dart:math';

void main() {
  var age=16;
  print(age);
  age = 38;
  print(age);

  const x = 46;
  const y = 10;

  const answer1 = (x * 100) + y;
  const answer2 = (x * 100) + (y * 1000);
  const answer3 = (x * 100) + ( y / 10);

  print ('Answers ${answer1} ${answer2} ${answer3}');

  double rating1 = 10.0;
  double rating2 = 20.0;
  double rating3 = 30.0;

  double averageRating = (rating1 + rating2 + rating3) / 3;

  print(averageRating);

//   double a = 2.0;
//   double b = 3.0;
//   double c = 1.0;

//   double root1 = (-b + sqrt((b*b) - (4*a*c))) / (2*a);
//   double root2 = (-b - sqrt((b*b) - (4*a*c))) / (2*a);

//   print ('The roots are ${root1} and ${root2}');


  const a = 2.0;
  const b = 3.0;
  const c = 1.0;
  final root1 = (-b + sqrt(b * b - 4 * a * c)) / (2 * a);
  final root2 = (-b - sqrt(b * b - 4 * a * c)) / (2 * a);
  print(root1);
  print(root2);

}
```