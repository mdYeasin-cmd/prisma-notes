# Prisma Notes

### Covered topics in Module 22

- Components of Prisma
  1. Prisma Client
  2. Prisma Migrate
  3. Prisma Studio
- For small and mid-level project prisma orm is best option
- Insert Data
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

### Covered topics in Module 23

- Relations in Prisma
  1. One-to-one
  2. One-to-many
  3. Many-to-many
- We need to write relation code on that model which contain forign key
- If a key is construct by multiple table primary key, we called that composite key
- Fluent Api --> If we retrieve a table data by depending on another table, that called fluent api in prisma
- For console nested array of object, we can follow below way -->
  - console.dir(variable, { depth: Infinity })
- In prisma, for work with multiple row, we always use the [] sign
- We can go indepth relations by using nested inclue property
