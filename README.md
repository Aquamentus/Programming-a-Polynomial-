# Programming-a-Polynomial-
#ifndef BASIC_POLYNOMIAL_H
#define BASIC_POLYNOMIAL_H

tmeplate<class T>
class Polynomial
{
public:
  Polynomial(const T& = 1, const T& = 1, const T& = 1);
  Polynomial(const Polynomial&);
  T operator+(const Polynomial&, const Polynomial&);
  T operator*(const Polynomial&, const Polynomial&);
  void setCoefficiant(T,itorator);
  
private:
  vector< T > coefficiants;
  
}

#endif
