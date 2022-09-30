cmake_minimum_required(VERSION 3.16)
project(New-CS236-Project_1)

set(CMAKE_CXX_STANDARD 17)

add_executable(New-CS236-Project_1
        main.cpp
        Token.h
        String.h
        Add.h
        Automaton.h
        Colon.h
        ColonDash.h
        Comma.h
        Comment.h
        Facts.h
        ID.h
        Left_Paren.h
        Lexer.cpp
        Lexer.h
        Multiply.h
        Period.h
        Q_Mark.h
        Queries.h
        Right_Paren.h
        Rules.h
        Schemes.h)
