<template>
  <form>
    <div><br>
      <label>NIS</label>
      <input type="text" name="nis" placeholder="Masukan NIS" />
      <br><br>
      <label>Nama Lengkap</label>
      <input type="text" name="nama_lengkap" placeholder="Masukan Nama Lengkap" />
      <br><br>
      <label>Jenis Kelamin</label>
      <label><input type="radio" name="jenis_kelamin" value="L"/> L </label>
      <label><input type="radio" name="jenis_kelamin" value="P"/> P </label>
      <br>
      <label>Alamat</label>
      <textarea type="text" name="alamat" placeholder="Masukan Alamat Lengkap">
      </textarea>
      <br><br>
      <label>No Telp</label>
      <input type="text" name="no_telp" placeholder="Masukan Nomor Telepon" />
      <br><br>
      <label>Kelas</label>
      <select>
        <option>
        </option>
        </select>
        <br><br>
      <button type="submit">Simpan </button>
    </div>
  </form>
</template>

<script>
  export default {

  }
</script>
