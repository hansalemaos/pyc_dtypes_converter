# Converts Python variables to C variables and vice versa


```python
$pip install pyc-dtypes-converter
from pyc_dtypes_converter import (
    convert_B_to_py,
    convert_Bool_to_py,
    convert_H_to_py,
    convert_I_to_py,
    convert_L_to_py,
    convert_N_to_py,
    convert_P_to_py,
    convert_Q_to_py,
    convert_b_to_py,
    convert_bool_to_py,
    convert_c_to_py,
    convert_char_array_p_to_py,
    convert_char_array_s_to_py,
    convert_char_to_py,
    convert_d_to_py,
    convert_double_to_py,
    convert_f_to_py,
    convert_float_to_py,
    convert_h_to_py,
    convert_i_to_py,
    convert_int_to_py,
    convert_l_to_py,
    convert_long_long_to_py,
    convert_long_to_py,
    convert_n_to_py,
    convert_p_to_py,
    convert_q_to_py,
    convert_s_to_py,
    convert_short_to_py,
    convert_signed_char_to_py,
    convert_size_t_to_py,
    convert_ssize_t_to_py,
    convert_to_c,
    convert_to_c_B,
    convert_to_c_Bool,
    convert_to_c_H,
    convert_to_c_I,
    convert_to_c_L,
    convert_to_c_N,
    convert_to_c_P,
    convert_to_c_Q,
    convert_to_c_b,
    convert_to_c_bool,
    convert_to_c_c,
    convert_to_c_char,
    convert_to_c_char_array_p,
    convert_to_c_char_array_s,
    convert_to_c_d,
    convert_to_c_double,
    convert_to_c_f,
    convert_to_c_float,
    convert_to_c_h,
    convert_to_c_i,
    convert_to_c_int,
    convert_to_c_l,
    convert_to_c_long,
    convert_to_c_long_long,
    convert_to_c_n,
    convert_to_c_p,
    convert_to_c_q,
    convert_to_c_s,
    convert_to_c_short,
    convert_to_c_signed_char,
    convert_to_c_size_t,
    convert_to_c_ssize_t,
    convert_to_c_unsigned_char,
    convert_to_c_unsigned_int,
    convert_to_c_unsigned_long,
    convert_to_c_unsigned_long_long,
    convert_to_c_unsigned_short,
    convert_to_c_void,
    convert_to_py,
    convert_unsigned_char_to_py,
    convert_unsigned_int_to_py,
    convert_unsigned_long_long_to_py,
    convert_unsigned_long_to_py,
    convert_unsigned_short_to_py,
    convert_void_to_py,
    print_all_dtypes,
)

retu = convert_to_c("char", b"1", b"2")
print(retu)
retu = convert_to_c("signed_char", 44)
print(retu)
retu = convert_to_c("signed_char", 44, 66)
print(retu)
retu = convert_to_c("b", 44, 66)
print(retu)

retu = convert_to_c("unsigned_char", 44)
print(retu)
retu = convert_to_c("unsigned_char", 44, 66)
print(retu)
retu = convert_to_c("B", 44, 66)
print(retu)

retu = convert_to_c("Bool", 1)
print(retu)

retu = convert_to_c("short", 158)
print(retu)

retu = convert_to_c("unsigned_short", 158, 211)
print(retu)

retu = convert_to_c("int", 158)
print(retu)

retu = convert_to_c("int", 1561)
print(retu)
retu = convert_to_c("char", b"e")
print(retu)
retu = convert_to_c("c", b"x")
print(retu)
retu = convert_to_c("char", b"x", b"e", b"f")
print(retu)
retu = convert_to_c("c", b"x")
print(retu)
retu = convert_to_c("signed_char", 1)
print(retu)
retu = convert_to_c("b", 121)
print(retu)
retu = convert_to_c("signed_char", 3, 5)
print(retu)
retu = convert_to_c("b", 16, 11)
print(retu)
retu = convert_to_c("unsigned_char", 161)
print(retu)
retu = convert_to_c("B", 161)
print(retu)
retu = convert_to_c("unsigned_char", 161, 212)
print(retu)
retu = convert_to_c("B", 161, 11)
print(retu)
retu = convert_to_c("Bool", 161)
print(retu)
retu = convert_to_c("?", 161)
print(retu)
retu = convert_to_c("Bool", 161, 212)
print(retu)
retu = convert_to_c("?", 161, 11)
print(retu)
retu = convert_to_c("short", 161)
print(retu)
retu = convert_to_c("h", 161)
print(retu)
retu = convert_to_c("short", 161, 212)
print(retu)
retu = convert_to_c("h", 161, 11)
print(retu)
retu = convert_to_c("unsigned_short", 161)
print(retu)
retu = convert_to_c("H", 161)
print(retu)
retu = convert_to_c("unsigned_short", 161, 212)
print(retu)
retu = convert_to_c("H", 161, 11)
print(retu)
retu = convert_to_c("int", 161)
print(retu)
retu = convert_to_c("i", 161)
print(retu)
retu = convert_to_c("int", 161, 212)
print(retu)
retu = convert_to_c("i", 161, 11)
print(retu)
retu = convert_to_c("unsigned_int", 161)
print(retu)
retu = convert_to_c("I", 161)
print(retu)
retu = convert_to_c("unsigned_int", 161, 212)
print(retu)
retu = convert_to_c("I", 161, 11)
print(retu)
retu = convert_to_c("long", 161)
print(retu)
retu = convert_to_c("l", 161)
print(retu)
retu = convert_to_c("long", 161, 212)
print(retu)
retu = convert_to_c("l", 161, 11)
print(retu)
retu = convert_to_c("unsigned_long", 161)
print(retu)
retu = convert_to_c("L", 161)
print(retu)
retu = convert_to_c("unsigned_long", 161, 212)
print(retu)
retu = convert_to_c("L", 161, 11)
print(retu)
retu = convert_to_c("long_long", 161)
print(retu)
retu = convert_to_c("q", 161)
print(retu)
retu = convert_to_c("long_long", 161, 212)
print(retu)
retu = convert_to_c("q", 161, 11)
print(retu)
retu = convert_to_c("unsigned_long_long", 161)
print(retu)
retu = convert_to_c("Q", 161)
print(retu)
retu = convert_to_c("unsigned_long_long", 161, 212)
print(retu)
retu = convert_to_c("Q", 161, 11)
print(retu)
retu = convert_to_c("ssize_t", 161)
print(retu)
retu = convert_to_c("n", 161)
print(retu)
retu = convert_to_c("ssize_t", 161, 212)
print(retu)
retu = convert_to_c("n", 161, 11)
print(retu)
retu = convert_to_c("size_t", 161)
print(retu)
retu = convert_to_c("N", 161)
print(retu)
retu = convert_to_c("size_t", 161, 212)
print(retu)
retu = convert_to_c("N", 161, 11)
print(retu)
retu = convert_to_c("float", 161)
print(retu)
retu = convert_to_c("f", 161)
print(retu)
retu = convert_to_c("float", 161, 212)
print(retu)
retu = convert_to_c("f", 161, 11)
print(retu)
retu = convert_to_c("double", 161)
print(retu)
retu = convert_to_c("d", 161)
print(retu)
retu = convert_to_c("double", 161, 212)
print(retu)
retu = convert_to_c("d", 161, 11)
print(retu)
retu = convert_to_c("char_array_s", b"1")
print(retu)
retu = convert_to_c("s", b"1")
print(retu)
retu = convert_to_c("char_array_s", b"161,212")
print(retu)
retu = convert_to_c("s", b"xx161,11")
print(retu)
retu = convert_to_c("char_array_p", b"1vbv61")
print(retu)
retu = convert_to_c("p", b"161")
print(retu)
retu = convert_to_c("char_array_p", b"161,212")
print(retu)
retu = convert_to_c("p", b"161,11")
print(retu)
retu = convert_to_c("void", 161)
print(retu)
retu = convert_to_c("P", 161)
print(retu)
retu = convert_to_c("void", 161, 212)
print(retu)
retu = convert_to_c("P", 161, 11)
print(retu)


args = [b"1", b"b"]
print(f"{convert_to_c_char(*args)=}")
print(f"{convert_to_c_c(*args)=}")
args = [11, 55]
print(f"{convert_to_c_signed_char(*args)=}")
print(f"{convert_to_c_b(*args)=}")
args = [11, 55]
print(f"{convert_to_c_unsigned_char(*args)=}")
print(f"{convert_to_c_B(*args)=}")
args = [11, 55]
print(f"{convert_to_c_Bool(*args)=}")
print(f"{convert_to_c_bool(*args)=}")
args = [11, 55]
print(f"{convert_to_c_short(*args)=}")
print(f"{convert_to_c_h(*args)=}")
args = [11, 55]
print(f"{convert_to_c_unsigned_short(*args)=}")
print(f"{convert_to_c_H(*args)=}")
args = [11, 55]
print(f"{convert_to_c_int(*args)=}")
print(f"{convert_to_c_i(*args)=}")
args = [11, 55]
print(f"{convert_to_c_unsigned_int(*args)=}")
print(f"{convert_to_c_I(*args)=}")
args = [11, 55]
print(f"{convert_to_c_long(*args)=}")
print(f"{convert_to_c_l(*args)=}")
args = [11, 55]
print(f"{convert_to_c_unsigned_long(*args)=}")
print(f"{convert_to_c_L(*args)=}")
args = [11, 55]
print(f"{convert_to_c_long_long(*args)=}")
print(f"{convert_to_c_q(*args)=}")
args = [11, 55]
print(f"{convert_to_c_unsigned_long_long(*args)=}")
print(f"{convert_to_c_Q(*args)=}")
args = [11, 55]
print(f"{convert_to_c_ssize_t(*args)=}")
print(f"{convert_to_c_n(*args)=}")
args = [11, 55]
print(f"{convert_to_c_size_t(*args)=}")
print(f"{convert_to_c_N(*args)=}")
args = [11, 55]
print(f"{convert_to_c_float(*args)=}")
print(f"{convert_to_c_f(*args)=}")
args = [11, 55]
print(f"{convert_to_c_double(*args)=}")
print(f"{convert_to_c_d(*args)=}")
args = [b"11"]
print(f"{convert_to_c_char_array_s(*args)=}")
print(f"{convert_to_c_s(*args)=}")
args = [b"11"]
print(f"{convert_to_c_char_array_p(*args)=}")
print(f"{convert_to_c_p(*args)=}")
args = [11]
print(f"{convert_to_c_void(*args)=}")
print(f"{convert_to_c_P(*args)=}")


print(convert_char_to_py(b=b"D"))
print(convert_c_to_py(b=b"D"))
print(convert_signed_char_to_py(b=b"D"))
print(convert_b_to_py(b=b"D"))
print(convert_unsigned_char_to_py(b=b"D"))
print(convert_B_to_py(b=b"D"))
print(convert_Bool_to_py(b=b"D"))
print(convert_bool_to_py(b=b"D"))
print(convert_short_to_py(b=b"11"))
print(convert_h_to_py(b=b"11"))
print(convert_unsigned_short_to_py(b=b"11"))
print(convert_H_to_py(b=b"11"))
print(convert_int_to_py(b=b"1111"))
print(convert_i_to_py(b=b"1111"))
print(convert_unsigned_int_to_py(b=b"2211"))
print(convert_I_to_py(b=b"2222"))
print(convert_long_to_py(b=b"2222"))
print(convert_l_to_py(b=b"1111"))
print(convert_unsigned_long_to_py(b=b"1111"))
print(convert_L_to_py(b=b"1111"))
print(convert_long_long_to_py(b=b"11112222"))
print(convert_q_to_py(b=b"11112222"))
print(convert_unsigned_long_long_to_py(b=b"22223333"))
print(convert_Q_to_py(b=b"11111111"))
print(convert_ssize_t_to_py(b=b"11111111"))
print(convert_n_to_py(b=b"11111111"))
print(convert_size_t_to_py(b=b"11111111"))
print(convert_N_to_py(b=b"11111111"))
print(convert_float_to_py(b=b"11111111"))
print(convert_f_to_py(b=b"11111111"))
print(convert_double_to_py(b=b"11111111"))
print(convert_d_to_py(b=b"11111111"))
print(convert_char_array_s_to_py(b=b"11111111"))
print(convert_s_to_py(b=b"11111111"))
print(convert_char_array_p_to_py(b=b"11111111"))
print(convert_p_to_py(b=b"11111111"))
print(convert_void_to_py(b=b"11111111"))
print(convert_P_to_py(b=b"11111111"))


# own format
print(convert_to_c(">bhl", 1, 2, 3))
print(convert_to_c("bhl", 1, 2, 3))
print(convert_to_py("bhl", b"\x01\x00\x02\x00\x03\x00\x00\x00"))
print(convert_to_py(">bhl", b"\x01\x00\x02\x00\x00\x00\x03"))

print_all_dtypes()



b'12'
b','
b',B'
b',B'
b','
b',B'
b',B'
b'\x01'
b'\x9e\x00'
b'\x9e\x00\xd3\x00'
b'\x9e\x00\x00\x00'
b'\x19\x06\x00\x00'
b'e'
b'x'
b'xef'
b'x'
b'\x01'
b'y'
b'\x03\x05'
b'\x10\x0b'
b'\xa1'
b'\xa1'
b'\xa1\xd4'
b'\xa1\x0b'
b'\x01'
b'\x01'
b'\x01\x01'
b'\x01\x01'
b'\xa1\x00'
b'\xa1\x00'
b'\xa1\x00\xd4\x00'
b'\xa1\x00\x0b\x00'
b'\xa1\x00'
b'\xa1\x00'
b'\xa1\x00\xd4\x00'
b'\xa1\x00\x0b\x00'
b'\xa1\x00\x00\x00'
b'\xa1\x00\x00\x00'
b'\xa1\x00\x00\x00\xd4\x00\x00\x00'
b'\xa1\x00\x00\x00\x0b\x00\x00\x00'
b'\xa1\x00\x00\x00'
b'\xa1\x00\x00\x00'
b'\xa1\x00\x00\x00\xd4\x00\x00\x00'
b'\xa1\x00\x00\x00\x0b\x00\x00\x00'
b'\xa1\x00\x00\x00'
b'\xa1\x00\x00\x00'
b'\xa1\x00\x00\x00\xd4\x00\x00\x00'
b'\xa1\x00\x00\x00\x0b\x00\x00\x00'
b'\xa1\x00\x00\x00'
b'\xa1\x00\x00\x00'
b'\xa1\x00\x00\x00\xd4\x00\x00\x00'
b'\xa1\x00\x00\x00\x0b\x00\x00\x00'
b'\xa1\x00\x00\x00\x00\x00\x00\x00'
b'\xa1\x00\x00\x00\x00\x00\x00\x00'
b'\xa1\x00\x00\x00\x00\x00\x00\x00\xd4\x00\x00\x00\x00\x00\x00\x00'
b'\xa1\x00\x00\x00\x00\x00\x00\x00\x0b\x00\x00\x00\x00\x00\x00\x00'
b'\xa1\x00\x00\x00\x00\x00\x00\x00'
b'\xa1\x00\x00\x00\x00\x00\x00\x00'
b'\xa1\x00\x00\x00\x00\x00\x00\x00\xd4\x00\x00\x00\x00\x00\x00\x00'
b'\xa1\x00\x00\x00\x00\x00\x00\x00\x0b\x00\x00\x00\x00\x00\x00\x00'
b'\xa1\x00\x00\x00\x00\x00\x00\x00'
b'\xa1\x00\x00\x00\x00\x00\x00\x00'
b'\xa1\x00\x00\x00\x00\x00\x00\x00\xd4\x00\x00\x00\x00\x00\x00\x00'
b'\xa1\x00\x00\x00\x00\x00\x00\x00\x0b\x00\x00\x00\x00\x00\x00\x00'
b'\xa1\x00\x00\x00\x00\x00\x00\x00'
b'\xa1\x00\x00\x00\x00\x00\x00\x00'
b'\xa1\x00\x00\x00\x00\x00\x00\x00\xd4\x00\x00\x00\x00\x00\x00\x00'
b'\xa1\x00\x00\x00\x00\x00\x00\x00\x0b\x00\x00\x00\x00\x00\x00\x00'
b'\x00\x00!C'
b'\x00\x00!C'
b'\x00\x00!C\x00\x00TC'
b'\x00\x00!C\x00\x000A'
b'\x00\x00\x00\x00\x00 d@'
b'\x00\x00\x00\x00\x00 d@'
b'\x00\x00\x00\x00\x00 d@\x00\x00\x00\x00\x00\x80j@'
b'\x00\x00\x00\x00\x00 d@\x00\x00\x00\x00\x00\x00&@'
b'1'
b'1'
b'1'
b'x'
b'\x00'
b'\x00'
b'\x00'
b'\x00'
b'\xa1\x00\x00\x00\x00\x00\x00\x00'
b'\xa1\x00\x00\x00\x00\x00\x00\x00'
b'\xa1\x00\x00\x00\x00\x00\x00\x00\xd4\x00\x00\x00\x00\x00\x00\x00'
b'\xa1\x00\x00\x00\x00\x00\x00\x00\x0b\x00\x00\x00\x00\x00\x00\x00'
convert_to_c_char(*args)=b'1b'
convert_to_c_c(*args)=b'1b'
convert_to_c_signed_char(*args)=b'\x0b7'
convert_to_c_b(*args)=b'\x0b7'
convert_to_c_unsigned_char(*args)=b'\x0b7'
convert_to_c_B(*args)=b'\x0b7'
convert_to_c_Bool(*args)=b'\x01\x01'
convert_to_c_bool(*args)=b'\x01\x01'
convert_to_c_short(*args)=b'\x0b\x007\x00'
convert_to_c_h(*args)=b'\x0b\x007\x00'
convert_to_c_unsigned_short(*args)=b'\x0b\x007\x00'
convert_to_c_H(*args)=b'\x0b\x007\x00'
convert_to_c_int(*args)=b'\x0b\x00\x00\x007\x00\x00\x00'
convert_to_c_i(*args)=b'\x0b\x00\x00\x007\x00\x00\x00'
convert_to_c_unsigned_int(*args)=b'\x0b\x00\x00\x007\x00\x00\x00'
convert_to_c_I(*args)=b'\x0b\x00\x00\x007\x00\x00\x00'
convert_to_c_long(*args)=b'\x0b\x00\x00\x007\x00\x00\x00'
convert_to_c_l(*args)=b'\x0b\x00\x00\x007\x00\x00\x00'
convert_to_c_unsigned_long(*args)=b'\x0b\x00\x00\x007\x00\x00\x00'
convert_to_c_L(*args)=b'\x0b\x00\x00\x007\x00\x00\x00'
convert_to_c_long_long(*args)=b'\x0b\x00\x00\x00\x00\x00\x00\x007\x00\x00\x00\x00\x00\x00\x00'
convert_to_c_q(*args)=b'\x0b\x00\x00\x00\x00\x00\x00\x007\x00\x00\x00\x00\x00\x00\x00'
convert_to_c_unsigned_long_long(*args)=b'\x0b\x00\x00\x00\x00\x00\x00\x007\x00\x00\x00\x00\x00\x00\x00'
convert_to_c_Q(*args)=b'\x0b\x00\x00\x00\x00\x00\x00\x007\x00\x00\x00\x00\x00\x00\x00'
convert_to_c_ssize_t(*args)=b'\x0b\x00\x00\x00\x00\x00\x00\x007\x00\x00\x00\x00\x00\x00\x00'
convert_to_c_n(*args)=b'\x0b\x00\x00\x00\x00\x00\x00\x007\x00\x00\x00\x00\x00\x00\x00'
convert_to_c_size_t(*args)=b'\x0b\x00\x00\x00\x00\x00\x00\x007\x00\x00\x00\x00\x00\x00\x00'
convert_to_c_N(*args)=b'\x0b\x00\x00\x00\x00\x00\x00\x007\x00\x00\x00\x00\x00\x00\x00'
convert_to_c_float(*args)=b'\x00\x000A\x00\x00\\B'
convert_to_c_f(*args)=b'\x00\x000A\x00\x00\\B'
convert_to_c_double(*args)=b'\x00\x00\x00\x00\x00\x00&@\x00\x00\x00\x00\x00\x80K@'
convert_to_c_d(*args)=b'\x00\x00\x00\x00\x00\x00&@\x00\x00\x00\x00\x00\x80K@'
convert_to_c_char_array_s(*args)=b'1'
convert_to_c_s(*args)=b'1'
convert_to_c_char_array_p(*args)=b'\x00'
convert_to_c_p(*args)=b'\x00'
convert_to_c_void(*args)=b'\x0b\x00\x00\x00\x00\x00\x00\x00'
convert_to_c_P(*args)=b'\x0b\x00\x00\x00\x00\x00\x00\x00'
(b'D',)
(b'D',)
(68,)
(68,)
(68,)
(68,)
(True,)
(True,)
(12593,)
(12593,)
(12593,)
(12593,)
(825307441,)
(825307441,)
(825307698,)
(842150450,)
(842150450,)
(825307441,)
(825307441,)
(825307441,)
(3617008641886990641,)
(3617008641886990641,)
(3689348814725067314,)
(3544668469065756977,)
(3544668469065756977,)
(3544668469065756977,)
(3544668469065756977,)
(3544668469065756977,)
(2.5784852031307537e-09, 2.5784852031307537e-09)
(2.5784852031307537e-09, 2.5784852031307537e-09)
(9.730415951366742e-72,)
(9.730415951366742e-72,)
(b'11111111',)
(b'11111111',)
(b'1111111',)
(b'1111111',)
(3544668469065756977,)
(3544668469065756977,)
b'\x01\x00\x02\x00\x00\x00\x03'
b'\x01\x00\x02\x00\x03\x00\x00\x00'
(1, 2, 3)
(1, 2, 3)
key: char                        dtype: c
key: signed_char                 dtype: b
key: unsigned_char               dtype: B
key: Bool                        dtype: ?
key: short                       dtype: h
key: unsigned_short              dtype: H
key: int                         dtype: i
key: unsigned_int                dtype: I
key: long                        dtype: l
key: unsigned_long               dtype: L
key: long_long                   dtype: q
key: unsigned_long_long          dtype: Q
key: ssize_t                     dtype: n
key: size_t                      dtype: N
key: float                       dtype: f
key: double                      dtype: d
key: char_array_s                dtype: s
key: char_array_p                dtype: p
key: void                        dtype: P
key: c                           dtype: c
key: b                           dtype: b
key: B                           dtype: B
key: ?                           dtype: ?
key: h                           dtype: h
key: H                           dtype: H
key: i                           dtype: i
key: I                           dtype: I
key: l                           dtype: l
key: L                           dtype: L
key: q                           dtype: q
key: Q                           dtype: Q
key: n                           dtype: n
key: N                           dtype: N
key: f                           dtype: f
key: d                           dtype: d
key: s                           dtype: s
key: p                           dtype: p
key: P                           dtype: P


```