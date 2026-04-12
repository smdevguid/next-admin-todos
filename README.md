# Development
Pasos para levantar la app en desarrollo


1. Levantar la base de datos, el comando ejecutara el archivo docker-compose.yml e instalara la imagen de docker. Se debe tener docker desctop instalado
```
docker compose up -d
```

2. Renombrar el .env.template a .env
3. Reemplazar las variables de entorno
4. Ejecutar el SEED para [crear la base de datos local](localhost:3000/api/seed)
5. Ejecutar migrate prisma command

# Prisma commnads
```
npx prisma init
npx prisma migrate dev
npx prisma generate

```



# Prod


# Stage
