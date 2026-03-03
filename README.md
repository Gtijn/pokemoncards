mkdir -p ~/Downloads/svi && cd ~/Downloads/svi && \
for i in $(seq -f "%03g" 1 258); do
  curl -O "https://pokemoncardimages.pokedata.io/images/Scarlet+%26+Violet+Base/$i.webp"
done
