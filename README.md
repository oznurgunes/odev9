1)city tablosu ile country tablosunda bulunan şehir (city) ve ülke (country) isimlerini birlikte görebileceğimiz INNER JOIN sorgusunu yazınız.<br><code>
  select city,country from country
inner join city on city.country_id = country.country_id;
</code><br>
2)customer tablosu ile payment tablosunda bulunan payment_id ile customer tablosundaki first_name ve last_name isimlerini birlikte görebileceğimiz INNER JOIN sorgusunu yazınız.<br><code>
  select payment_id, first_name, last_name from payment
inner join customer on payment.customer_id = customer.customer_id;
</code><br>
3)customer tablosu ile rental tablosunda bulunan rental_id ile customer tablosundaki first_name ve last_name isimlerini birlikte görebileceğimiz INNER JOIN sorgusunu yazınız.<br><code>
  select rental_id , first_name,last_name from customer
inner join rental on customer.customer_id = rental.customer_id;
