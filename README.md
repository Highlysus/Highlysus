echo "# Highlysus" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/Highlysus/README.md.git
git push -u origin main
def fibonacci(n)
  return n if ( 0..1 ).include? n
  (fibonacci(n - 1) + fibonacci(n - 2)) #recursive calls
end