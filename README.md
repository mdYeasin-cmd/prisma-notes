# Prisma Notes

### Covered topics in Module 22

- Components of Prisma
  1. Prisma Client
  2. Prisma Migrate
  3. Prisma Studio
- For small and mid-level project prisma orm is best option
- Inset Data
  1. create()
  2. createMany()
- Find Data
  1. find()
  2. findMany()
- Update Data
  1. update()
  2. updateMany()
  3. upsert()
- Delete Data
  1. delete()
  2. deleteMany()
- Because of serial data type, id never repeat on same table
- Types of pagination
  1. Offset pagination --> Offset pagination is not useful for huge data (skip, take)
  2. Cursor based pagination --> In cursor based pagination we use a point to start pagination (skip, take, cursor)
