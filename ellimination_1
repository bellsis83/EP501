#!/usr/bin/env python3
# -*- coding: utf-8 -*-
"""
Created on Sun Jan 31 13:31:55 2021

@author: byonghoonseo
"""
# %% 
import numpy as np

A = np.array([[2,2],[3,4]])
B = np.array([[5,6],[7,8]])

C = np.matmul(A,B)
D = np.dot(A,B)

print(C)  # matmul product
print(D)  # dot product

# %% 

# to calculate linear equations

A1 = [[2,3],[2,-7]]
B1 = [[3],[8]]              # be careful, have to have each bracket!
A1_inv = np.linalg.inv(A1)  # inverse matrix

C1 = np.matmul(A1_inv,B1)   # calculate linear equation
print(C1)
D1 = np.dot(A1_inv,B1)
print(D1)
