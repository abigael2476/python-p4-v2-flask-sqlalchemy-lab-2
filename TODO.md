# TODO - Flask-SQLAlchemy Lab 2

## Task #1: Add Review Model and Relationships

- [x] Plan the Review model structure
- [ ] Add Review class with **tablename**, id, comment, customer_id, item_id
- [ ] Add customer and item relationships to Review
- [ ] Add reviews relationship to Customer
- [ ] Add reviews relationship to Item
- [ ] Run migrations: `flask db migrate -m 'add review'`
- [ ] Run upgrade: `flask db upgrade head`
- [ ] Run review tests: `pytest testing/review_test.py`

## Task #2: Add Association Proxy

- [ ] Add items association proxy to Customer model
- [ ] Run association proxy tests: `pytest testing/association_proxy_test.py`

## Task #3: Add Serialization

- [ ] Add SerializerMixin to Review model
- [ ] Add SerializerMixin to Customer model
- [ ] Add SerializerMixin to Item model
- [ ] Add serialization exclude rules to prevent recursion
- [ ] Run serialization tests: `pytest testing/serialization_test.py`

## Final Steps

- [ ] Run all tests: `pytest`
- [ ] Commit and push changes
