# Declaração de Classes

#### Estrutura básica de uma classe

public class Order {

​	// atributos e metodos

}

#### Estrutura com atributos e métodos:

public class Order {

​	// atributos

​	private final String code;

​	private final BigDecimal totalValue;



​	// metodos

​	public BigDecimal calculateFee(){

​	}

}

#### Estrutura completa de uma classe:

package com.dio.base;

import java.math.BigDecumal;

public class Order {

​	private final String code;

​	private final BigDecimal totalValue;

​	

​	public Order(String code, BigDecimal totalValue){

​		this.code = code.

​		this.totalValue = totalValue;

​	}

​	public BigDecimal calculateFee(){

​		return this.totalValue.multiply(new BigDecimal("0.99"));

​	}

}