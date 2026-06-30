# dedicated-server-criminal-spree

https://www.youtube.com/watch?v=RgmtdeBIZ2s

Want to go to jail? Just docker compose up -d

Estimate memory consumption: 13gb
I didn't bother testing if it actually works, but at least the images are downloaded and most containers seem to start so... I'll leave the rest of the tinkering to you.

# Quick Reference
Start everything:
  docker compose up -d

Stop everything:
  docker compose down

Stop and delete everything (volumes):
  docker compose down -v

View logs:
  docker compose logs -f [service-name]
