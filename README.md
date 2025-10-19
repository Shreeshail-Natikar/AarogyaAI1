
# Create README.md if it doesn't exist
if [ ! -f README.md ]; then
  echo "# AarogyaAI Flutter Project" > README.md
  git add README.md
  git commit -m "Add README.md"
fi
