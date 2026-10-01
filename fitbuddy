SQLite format 3@  .� ���6�Q�b3'yindexix_workout_plans_idworkout_plansCREATE INDEX ix_workout_plans_id ON workout_plans (id)r='� indexix_workout_plans_user_idworkout_plansCREATE INDEX ix_workout_plans_user_id ON workout_plans (user_id)�n''�tableworkout_plansworkout_plansCREATE TABLE workout_plans (
        id INTEGER NOT NULL, 
        user_id VARCHAR(50) NOT NULL, 
        original_plan TEXT NOT NULL, 
        updated_plan TEXT, 
        nutrition_tip TEXT, 
        feedback TEXT, 
        created_at DATETIME NOT NULL, 
        updated_at DATETIME NOT NULL, 
        PRIMARY KEY (id), 
        FOREIGN KEY(user_id) REFERENCES users (user_id) ON DELETE CASCADE
)X-{indexix_users_user_idusersCREATE UNIQUE INDEX ix_users_user_id ON users (user_id)B#Yindexix_users_idusersCREATE INDEX ix_users_id ON users (id)�)�1tableusersusersCREATE TABLE users (
        id INTEGER NOT NULL, 
        user_id VARCHAR(50) NOT NULL, 
        username VARCHAR(100) NOT NULL, 
        age INTEGER NOT NULL, 
        weight FLOAT NOT NULL, 
        goal VARCHAR(100) NOT NULL, 
        intensity VARCHAR(50) NOT NULL, 
        created_at DATETIME NOT NULL, 
        PRIMARY KEY (id)
) 