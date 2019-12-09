# Truthiness Quiz

## Objectives

- Strengthen your understanding of truthiness in Ruby
- Practice using boolean and comparison operators

???

# Quiz

?: `false && true`

( )`true` (X)`false`

?: `true && true`

(X)`true` ( )`false`

?: `"test" == "test"`

(X)`true` ( )`false`

?: `10 == 10 || 20 != 10`

(X)`true` ( )`false`

?: `10 == 10 && 20 == 10`

( )`true` (X)`false`

?: `true && 10 == 10`

(X)`true` ( )`false`

?: `true || 10 == 10`

(X)`true` ( )`false`

?: `false && 10 != 10`

( )`true` (X)`false`

?: `"boolean" == "booleans"`

( )`true` (X)`false`

?: `"boolean" != "booleans"`

(X)`true` ( )`false`

?: `10 != 0 && 20 == 10`

( )`true` (X)`false`

?: `"boolean" == 1`

( )`true` (X)`false`

?: `!(true && false)`

(X)`true` ( )`false`

?: `!(1000 == 1 || 10000 == 10000)`

( )`true` (X)`false`

?: `!(10 == 10 && 20 != 10)`

( )`true` (X)`false`

?: `!(1 != 100 || 30 == 40)`

( )`true` (X)`false`

?: `!("boolean" == "booleans" && "Code" == "Fun")`

(X)`true` ( )`false`

?: `1 == 1 && (!("boolean" == 1 || 1 == 0))`

(X)`true` ( )`false`

?: `"strong" == "coffee" && (!(30 == 40 || 30 == 30))`

( )`true` (X)`false`

?: `30 == 30 && (!("boolean" == "booleans" || "Coding" == "Awesome"))`

(X)`true` ( )`false`

?: Take a look at the code below. We have defined a method, `returning_true` that uses a comparison operator, the `<` (less than) to compare the number 14 to... nothing. What value(s) for `?` will make `returning_true` return `true`?

```ruby
def returning_true
  14 < ?
end
```

[ ] 1
[x] 15
[ ] 14
[x] 17

?: Here we have a method, `returning_false` that uses both comparison and boolean operators. What value(s) for `?` will make `returning_false` return `false`?

```ruby
def returning_false
  7 > 4 && 100 < ?
end
```

[x] 100
[ ] 101
[ ] 102
[ ] 103

?: Take a look at the method `using_truthiness` below. What value(s) for `?` will make `using_truthiness` return `false`?

```ruby
def using_truthiness
  7 > 8 || ?
end
```

[x] false
[x] 8 > 9
[x] !true
[ ] !false

?: What value(s) for `?` will make `using_truthiness` return `true`?

```ruby
def using_truthiness
  7 > 8 || ?
end
```

[x] 7 > 6
[ ] 7
[ ] false
[ ] 8 > 9

???

<p data-visibility='hidden'>View <a href='https://learn.co/lessons/truthiness-code-challenge' title='Truthiness Code Challenge'>Truthiness Code Challenge</a> on Learn.co and start learning to code for free.</p>
