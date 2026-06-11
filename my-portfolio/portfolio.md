# Create a new repository
mkdir my-portfolio
cd my-portfolio
git init

# Create initial portfolio file
cat > portfolio.md << 'EOF'
# My Portfolio

## About Me
Name: Gabriel Brito pINTO
Major: Computer Science

## Skills
- Programming: C++, JavaScript
- Git: Advanced
- Database: SQL
- Programming: Python, Java
- Git: Intermediat  e
- Web Development: HTML, CSS

## Projects
- Project 1: TBD
- Project 2: TBD

## Contact
Email: gbrito-pinto@myseneca.ca
EOF

git add portfolio.md
git commit -m "Initial portfolio"