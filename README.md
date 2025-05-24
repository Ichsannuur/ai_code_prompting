# Template Prompting untuk AI Code - 15 Use Cases

## 1. Template Membuat Feature Baru

```
Saya ingin membuat [NAMA_FEATURE] untuk aplikasi [BAHASA_PEMROGRAMAN/FRAMEWORK].

**Requirements:**
- [Requirement 1]
- [Requirement 2]
- [Requirement 3]

**Tech Stack:** [Stack yang digunakan]
**Expected Input:** [Format input]
**Expected Output:** [Format output]

Tolong buatkan:
1. Kode implementasi lengkap
2. Unit test
3. Contoh penggunaan
4. Error handling

Gunakan best practices dan tambahkan komentar yang jelas.
```

**Contoh Penggunaan:**
```
Saya ingin membuat sistem login untuk aplikasi Node.js Express.

**Requirements:**
- Autentikasi dengan email dan password
- JWT token untuk session
- Password hashing dengan bcrypt
- Rate limiting untuk prevent brute force

**Tech Stack:** Node.js, Express, MongoDB, JWT
**Expected Input:** {email: string, password: string}
**Expected Output:** {token: string, user: object} atau error message

Tolong buatkan:
1. Kode implementasi lengkap
2. Unit test
3. Contoh penggunaan
4. Error handling
```

## 2. Template Fix Bug

```
Saya memiliki bug di kode berikut:

**Kode yang bermasalah:**
```[BAHASA_PEMROGRAMAN]
[PASTE_KODE_DISINI]
```

**Error message:**
```
[PASTE_ERROR_MESSAGE]
```

**Expected behavior:** [Jelaskan apa yang seharusnya terjadi]
**Actual behavior:** [Jelaskan apa yang sebenarnya terjadi]
**Steps to reproduce:** 
1. [Step 1]
2. [Step 2]
3. [Step 3]

Tolong analisis dan perbaiki bug ini, serta jelaskan penyebabnya.


## 3. Template Code Review & Optimization

```
Tolong review kode berikut dan berikan saran perbaikan:

[BAHASA_PEMROGRAMAN]
[PASTE_KODE_DISINI]


**Fokus review pada:**
- [ ] Performance optimization
- [ ] Security issues
- [ ] Code readability
- [ ] Best practices
- [ ] Potential bugs
- [ ] Memory leaks

**Context:** [Jelaskan konteks penggunaan kode]
**Performance requirements:** [Jelaskan requirement performa jika ada]

Berikan rekomendasi dengan prioritas (High/Medium/Low) dan contoh implementasi yang diperbaiki.
```

## 4. Template Dokumentasi API

```
Buatkan dokumentasi lengkap untuk API endpoint berikut:

**Endpoint:** [HTTP_METHOD] [URL_PATH]
**Function name:** [NAMA_FUNCTION]

[BAHASA_PEMROGRAMAN]
[PASTE_KODE_FUNCTION]

**Format dokumentasi yang diinginkan:**
- [ ] OpenAPI/Swagger format
- [ ] Markdown format
- [ ] JSDoc format

**Yang harus include:**
- Description dan purpose
- Parameters (path, query, body)
- Response format dan status codes
- Error handling
- Example request/response
- Authentication requirements (jika ada)
```

## 5. Template Refactoring Code

```
Tolong refactor kode berikut untuk membuatnya lebih maintainable:

[BAHASA_PEMROGRAMAN]
[PASTE_KODE_DISINI]

**Refactoring goals:**
- [ ] Improve readability
- [ ] Reduce code duplication
- [ ] Better separation of concerns
- [ ] Follow [DESIGN_PATTERN] pattern
- [ ] Improve testability

**Constraints:**
- Maintain existing functionality
- [Constraint lainnya]

Berikan penjelasan setiap perubahan yang dilakukan dan alasannya.
```

## 6. Template Database Query Optimization

```
Saya memiliki query database yang slow, tolong optimasi:

**Database:** [MySQL/PostgreSQL/MongoDB/etc]
**Current query:**
[PASTE_QUERY_DISINI]


**Performance issue:**
- Query time: [WAKTU_EKSEKUSI]
- Table size: [JUMLAH_RECORDS]
- Frequency: [SEBERAPA_SERING_DIJALANKAN]

**Table schema:**
[PASTE_SCHEMA_JIKA_PERLU]

Tolong berikan:
1. Query yang dioptimasi
2. Index recommendations
3. Penjelasan mengapa lebih cepat
4. Alternative approaches jika ada
```

## 7. Template Testing Strategy

```
Buatkan comprehensive test suite untuk kode berikut:

[BAHASA_PEMROGRAMAN]
[PASTE_KODE_DISINI]

**Testing requirements:**
- [ ] Unit tests
- [ ] Integration tests
- [ ] Edge cases
- [ ] Error scenarios
- [ ] Performance tests

**Testing framework:** [Jest/PHPUnit/pytest/etc]
**Coverage target:** [PERSENTASE]%

**Scenarios to test:**
- [Scenario 1]
- [Scenario 2]
- [Edge case scenarios]

Sertakan mock objects dan test data yang diperlukan.
```

## 8. Template Architecture Design

```
Saya ingin membangun [NAMA_SISTEM/APLIKASI] dengan requirements berikut:

**Functional Requirements:**
- [Requirement 1]
- [Requirement 2]
- [Requirement 3]

**Non-functional Requirements:**
- Scale: [Jumlah users/requests]
- Performance: [Response time requirements]
- Availability: [Uptime requirements]
- Security: [Security requirements]

**Constraints:**
- Budget: [Budget constraints]
- Technology: [Tech stack preferences]
- Timeline: [Development timeline]

Tolong design:
1. System architecture diagram
2. Database schema
3. API design
4. Technology stack recommendations
5. Deployment strategy
```

## 9. Template Code Conversion

```
Tolong convert kode berikut dari [BAHASA_ASAL] ke [BAHASA_TUJUAN]:

**Source code ([BAHASA_ASAL]):**
[BAHASA_ASAL]
[PASTE_KODE_DISINI]

**Conversion requirements:**
- Maintain exact functionality
- Follow [BAHASA_TUJUAN] best practices
- Use appropriate libraries/frameworks
- Include error handling
- Add type hints/annotations (jika supported)

**Target framework/library:** [Jika ada specific framework]

Berikan penjelasan perbedaan approach antara kedua bahasa dan trade-offs yang ada.
```

## 10. Template Security Audit

```
Tolong lakukan security audit untuk kode berikut:

[BAHASA_PEMROGRAMAN]
[PASTE_KODE_DISINI]

**Security checklist:**
- [ ] Input validation
- [ ] SQL injection prevention
- [ ] XSS prevention
- [ ] Authentication/Authorization
- [ ] Data encryption
- [ ] Rate limiting
- [ ] CORS configuration
- [ ] Error information disclosure

**Application type:** [Web app/API/Mobile app/etc]
**Security level required:** [Low/Medium/High/Critical]

Berikan:
1. Vulnerability assessment
2. Risk level (Critical/High/Medium/Low)
3. Remediation steps
4. Secure code examples
```

## 11. Template Performance Profiling

```
Kode berikut memiliki performance issue, tolong analisis dan optimasi:

[BAHASA_PEMROGRAMAN]
[PASTE_KODE_DISINI]

**Performance metrics:**
- Current execution time: [WAKTU]
- Memory usage: [MEMORY_USAGE]
- CPU usage: [CPU_USAGE]
- Target performance: [TARGET_METRICS]

**Profiling data:**
[PASTE_PROFILING_RESULTS_JIKA_ADA]

**Usage context:**
- Frequency of execution: [FREQUENCY]
- Data size: [DATA_SIZE]
- Concurrent users: [CONCURRENCY]

Berikan:
1. Bottleneck analysis
2. Optimized code
3. Performance comparison
4. Monitoring recommendations
```

## 12. Template Integration Development

```
Saya perlu mengintegrasikan dengan [NAMA_SERVICE/API] berikut:

**Service details:**
- API Documentation: [LINK_DOKUMENTASI]
- Authentication: [AUTH_METHOD]
- Rate limits: [RATE_LIMITS]
- Base URL: [BASE_URL]

**Integration requirements:**
- [Requirement 1]
- [Requirement 2]
- [Error handling strategy]
- [Retry mechanism]

**Expected operations:**
- [Operation 1]: [Description]
- [Operation 2]: [Description]

Tolong buatkan:
1. Integration layer/wrapper
2. Error handling
3. Rate limiting handling
4. Unit tests
5. Usage examples
6. Configuration management
```

## 13. Template Legacy Code Modernization

```
Tolong modernize legacy code berikut:

**Legacy code:**
[BAHASA_PEMROGRAMAN]
[PASTE_LEGACY_CODE]


**Current issues:**
- [Issue 1]
- [Issue 2]
- [Deprecated features used]

**Modernization goals:**
- [ ] Update to latest language version
- [ ] Replace deprecated functions
- [ ] Improve error handling
- [ ] Add type safety
- [ ] Better logging
- [ ] Configuration management

**Constraints:**
- Must maintain backward compatibility
- [Constraint lainnya]

**Target version:** [LANGUAGE_VERSION]

Berikan migration plan step-by-step dan highlight breaking changes.
```

## 14. Template CI/CD Pipeline

```
Buatkan CI/CD pipeline untuk project berikut:

**Project details:**
- Language/Framework: [TECH_STACK]
- Repository: [GIT_PLATFORM]
- Deployment target: [CLOUD_PROVIDER/SERVER]
- Testing framework: [TESTING_TOOLS]

**Pipeline requirements:**
- [x] Automated testing
- [x] Code quality checks
- [x] Security scanning
- [x] Build automation
- [x] Deployment automation

**Deployment stages:**
- Development
- Staging
- Production

**Tools preference:** [GitHub Actions/GitLab CI/Jenkins/etc]

Tolong buatkan:
1. Pipeline configuration file
2. Build scripts
3. Deployment scripts
4. Environment configuration
5. Monitoring setup
```

## 15. Template Code Migration

```
Saya perlu migrate aplikasi dari [PLATFORM_LAMA] ke [PLATFORM_BARU]:

**Current application:**
- Framework: [FRAMEWORK_LAMA]
- Database: [DATABASE_LAMA]
- Architecture: [ARCHITECTURE_LAMA]

**Target application:**
- Framework: [FRAMEWORK_BARU]
- Database: [DATABASE_BARU]
- Architecture: [ARCHITECTURE_BARU]

**Migration scope:**
- [ ] Database schema
- [ ] Business logic
- [ ] API endpoints
- [ ] Authentication system
- [ ] File storage
- [ ] Configuration

**Constraints:**
- Zero downtime requirement
- Data integrity must be maintained
- [Constraint lainnya]

Tolong buatkan:
1. Migration strategy
2. Data migration scripts
3. Code conversion plan
4. Testing strategy
5. Rollback plan
6. Timeline estimation
```

## Tips Tambahan untuk Effective Prompting:

### 1. Gunakan Context yang Jelas
- Selalu berikan informasi tech stack
- Jelaskan constraint dan requirement
- Sertakan contoh input/output yang diharapkan

### 2. Spesifikasi Format Output
- Request format kode yang diinginkan
- Tentukan level detail dokumentasi
- Minta penjelasan step-by-step jika perlu

### 3. Include Error Scenarios
- Minta handling untuk edge cases
- Spesifikasikan error handling yang dibutuhkan
- Request validation dan sanitization

### 4. Best Practices Request
- Minta implementasi sesuai industry standards
- Request security considerations
- Minta performance optimization tips

### 5. Testing Requirements
- Selalu minta contoh testing
- Spesifikasikan coverage yang dibutuhkan
- Request integration testing examples

Gunakan template ini sebagai starting point dan sesuaikan dengan kebutuhan spesifik project Anda!
