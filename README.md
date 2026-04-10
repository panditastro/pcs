  INSERT INTO Users 
(Email, PasswordHash, FullName, Role, IsActive, IsEmailVerified, CreatedAt)
VALUES (
  'superadmin@test.com',
  '$2a$11$8K1pQ9G7xFZC6dYw2y7QeOq7l6kQy2n9Z0QjK7XbJ8kL9mN1p2r3S', -- password: 123456
  'Super Admin',
  'Admin',  Admin role
  1,
  1,  -- email verified
  GETUTCDATE()
);
