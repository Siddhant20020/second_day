ENTITY: User
Attributes: UserID (Primary Key), Username, Email

ENTITY: Account
Attributes: AccountID (Primary Key), UserID (Foreign Key), AccountType, Username, Password

ENTITY: PasswordGenerator
Attributes: GeneratorID (Primary Key), UserID (Foreign Key), ComplexityLevel

ENTITY: Session
Attributes: SessionID (Primary Key), UserID (Foreign Key), LoginTime, LogoutTime

RELATIONSHIP: User -< Account
Relationship Type: One-to-Many

RELATIONSHIP: User -< PasswordGenerator
Relationship Type: One-to-Many

RELATIONSHIP: User -< Session
Relationship Type: One-to-Many
