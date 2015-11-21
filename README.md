# Daftar Siswa
# Penguuman
# Notifikasi Email

-- Role --
* Admin
* User Biasa (Tukang Seleksi)
* User Siswa

-- Tabel --
# Users
    *id
    *email
    *password
    *role_id
# Roles
    *id
    *name -> [admin, staff, pre_student]
# Permissions
    *id
    *permission_name
    *role_id
# Applicants
    *id
    *user_id
    *name
    *date_of_birth
    *address
    *middle_scholl
    *middle_school_address
    *date_of_graduate
    *math_score
    *english_score
    *indonesian_score
    *science_score
    *average_score
    *handphone_number
    *parent_name
    *document_graduate
    *reg_number
# Accepted_applicants
    *id
    *academic_year_id
    *applicant_id
    *predicat
    *total_score
# Exam_results
    *id
    *applicant_id
    *math_score
    *english_score
    *indonesian_score
    *science_score
# Academic_years
    *id
    *year# PSB-Theme
