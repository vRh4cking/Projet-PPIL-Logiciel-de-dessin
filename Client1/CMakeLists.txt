cmake_minimum_required(VERSION 3.17)
project(Client)

set(CMAKE_CXX_STANDARD 14)

include_directories(Client)

add_executable(Client
        Forme/Cercle.cpp
        Forme/Cercle.h
        Sauvegarde/ChargeurForme.cpp
        Sauvegarde/ChargeurForme.h
        Forme/CmpF2D.h
        DessinJava/Dessiner.h
        DessinJava/DessinJ.cpp
        DessinJava/DessinJ.h
        Erreur.cpp
        Erreur.h
        Forme/Forme2D.cpp
        Forme/Forme2D.h
        Forme/FormeComp.cpp
        Forme/FormeComp.h
        Forme/FormeSimple.cpp
        Forme/FormeSimple.h
        Transformations/Homoth.cpp
        Transformations/Homoth.h
        main.cpp
        Geom/Matrice22.cpp
        Geom/Matrice22.h
        Parseurs/ParseurCercle.cpp
        Parseurs/ParseurCercle.h
        Parseurs/ParseurBase.h
        Parseurs/ParseurFormes.cpp
        Parseurs/ParseurFormes.h
        Parseurs/ParseurFormeComp.cpp
        Parseurs/ParseurFormeComp.h
        Parseurs/ParseurPoly.cpp
        Parseurs/ParseurPoly.h
        Parseurs/ParseurSeg.cpp
        Parseurs/ParseurSeg.h
        Parseurs/ParseurTri.cpp
        Parseurs/ParseurTri.h
        Forme/Polygone.cpp
        Forme/Polygone.h
        Transformations/Rotation.cpp
        Transformations/Rotation.h
        Sauvegarde/Sauvegarde.cpp
        Sauvegarde/Sauvegarde.h
        Sauvegarde/SauveText.cpp
        Sauvegarde/SauveText.h
        Forme/Segment.cpp
        Forme/Segment.h
        DessinJava/Socket.cpp
        DessinJava/Socket.h
        Transformations/Transform.cpp
        Transformations/Transform.h
        Transformations/Transla.cpp
        Transformations/Transla.h
        Forme/Triangle.cpp
        Forme/Triangle.h
        Geom/Vecteur2D.cpp
        Geom/Vecteur2D.h)
